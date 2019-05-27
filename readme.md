## 1) The most basic netlify functions example:
https://flaviocopes.com/netlify-functions/

## 2) Add CORS so you can access your function as needed
`exports.handler = (event, context, callback) => {
  callback(null, {
    statusCode: 200,
    body: 'No worries, all is working fine!',
    headers: {
      'Access-Control-Allow-Origin': '*'
    },
  })
}`

## 3) Connect your netlify function up to faunadb
???

profit