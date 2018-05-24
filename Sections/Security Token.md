Security Token
============================

Clients are able to use _Device ID_ and _Device Password_ ([How to Create Device ID and Device Password](https://github.com/PayFabric/Portal/blob/v2/Sections/Quick%20Start.md#define-devices)) to generate _Security Tokens_.
Security tokens are one-time use authorization credentials. You should only use this authentication method in secure environments. 

Generate Security Token C# Sample Code Snippet
--------------

                // Replace url when going live
                var url = "https://sandbox.payfabric.com/v2/rest/api/token/create";

                HttpWebRequest httpWebRequest = WebRequest.Create(url) as HttpWebRequest;
                httpWebRequest.ContentType = "application/json; charset=utf-8";
                httpWebRequest.Method = "GET";

                // Replace with your own device id and device password
                httpWebRequest.Headers["authorization"] = "0ad64468-f4bc-0c99-4e31-bd08dd862c43|123456abc";
                
                ServicePointManager.SecurityProtocol = SecurityProtocolType.Tls12;
                
                HttpWebResponse httpWebResponse = httpWebRequest.GetResponse() as HttpWebResponse;
                Stream responseStream = httpWebResponse.GetResponseStream();
                StreamReader streamReader = new StreamReader(responseStream);
                string result = streamReader.ReadToEnd();
                streamReader.Close();
                responseStream.Close();
                httpWebRequest.Abort();
                httpWebResponse.Close();
