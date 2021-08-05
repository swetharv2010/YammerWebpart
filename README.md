# yammerWebpart

<!DOCTYPE HTML>
<html lang="">
<head>
<title>Yammer Embed Feed</title>
<style type="text/css">
iframe {
color: white;
}
</style>
<script src="https://code.jquery.com/jquery-1.9.1.min.js">
</head>
<body>
<script type="text/javascript" src="https://c64.assets-yammer.com/assets/platform_embed.js">



<div id="embedded-feed" style="height:400px;width:500px;"></div>
<script>
yam.connect.embedFeed({
container: '#embedded-feed',
network: 'ericsson.com',
feedType: 'topic',
feedId: 22643221,
config: {
header: true,
footer: true,
showOpenGraphPreview: false,
}
});
</script>



</body>
</html>
