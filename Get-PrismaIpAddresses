$key = "<API-Key goes here>"
$prismaUrl = "https://api.prod.datapath.prismaaccess.com/getPrismaAccessIP/v2"
$header = @{"header-api-key" = $key}
$params = @"
{
 "serviceType":"all",
 "addrType":"all",
 "location":"all"
}
"@

$results = Invoke-restmethod -Method Post -Headers $header -Uri $prismaUrl -body $params -ContentType application/json
