# Enhanced-proxy-detection

Enthanced Proxy Detection is my previous employer's (Akamai) project. Since it is a company owned project, I dont have access to code base.

# Project description
  Akamai customers need the ability to restrict access to their content in accordance with their content rights agreements.Customers are increasingly being challenged by location spoofing services that are specifically designed to defeat regional restrictions of popular OTT services.For example, if you are an end-user outside of the UK looking to access BBC content, you might try to enlist the aid of a VPN provider that makes your connecting IP address appear as if it was coming from somewhere within the UK. This is problematic for BBC as they may charge difference license fees depending on what region the content is consumed in, and therefore this location spoofing service is affecting BBC’s bottom line.
  
  Enhanced Proxy Detection, or EPD, is the enablement of third-party IP metadata within the Akamai network to identify IP addresses originating from location spoofing services, and provides our customers with the tools to both block, allow, and monitor how these services are being utilized to access their content.

Ghost modifications to: 
* Access third-party IP metadata in a manner that utilizes memory efficiently and allows for fast access
* Based on connecting IP, identify and classify incoming requests using third-party IP metadata 
* Act upon requests based on customer rules configured on the property in Portal
