# hub-oauth-client

The OAuth client metadata document for one person's own trading desk (an MCP client of Questrade's
MCP server). `client.json` names the client and its loopback redirect addresses so the authorization
server can identify it. It holds no secrets and grants nothing by itself: every token still comes
from the operator signing in and consenting, and every order still needs his approval on his phone.
