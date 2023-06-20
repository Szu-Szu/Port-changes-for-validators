# Port-changes-for-validators
<h1>First change the ports in the app.toml</h1>
*change the api port
*change the grpc port
*change the grpc-web port

<h1> Second change the ports in the config.toml</h1>
*change the proxy app port
*change the rpc port
*allow any origins for cors
*change the pprof_laddr port
*change the p2p port

<h1>Third change the port in the client.toml</h1>
*change the node port to the same as the port as the rpc port in the config.toml
