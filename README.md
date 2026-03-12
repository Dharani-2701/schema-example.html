<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>JSON-LD Schema Markup Example</title>

<!-- Organization Schema -->
<script type="application/ld+json">
{
 "@context": "https://schema.org",
 "@type": "Organization",
 "name": "Example Organization",
 "url": "https://www.example.com",
 "logo": "https://www.example.com/logo.png",
 "contactPoint": {
   "@type": "ContactPoint",
   "telephone": "+91-0000000000",
   "contactType": "customer support",
   "areaServed": "IN",
   "availableLanguage": "English"
 },
 "sameAs": [
   "https://www.linkedin.com/",
   "https://www.twitter.com/"
 ]
}
</script>

<!-- Website Schema -->
<script type="application/ld+json">
{
 "@context": "https://schema.org",
 "@type": "WebSite",
 "name": "Example Website",
 "url": "https://www.example.com",
 "potentialAction": {
   "@type": "SearchAction",
   "target": "https://www.example.com/search?q={search_term_string}",
   "query-input": "required name=search_term_string"
 }
}
</script>

</head>

<body>
<h1>JSON-LD Schema Markup Example</h1>
<p>This page demonstrates how structured data can be implemented using JSON-LD to improve search engine understanding and SEO.</p>
</body>
</html>
