curl -X POST "http://host.docker.internal:7070/realms/fhir-realm/protocol/openid-connect/token" \
  -H "Content-Type: application/x-www-form-urlencoded" \
  -d "grant_type=password" \
  -d "client_id=fhir-client" \
  -d "client_secret=secret" \
  -d "username=testuser" \
  -d "password=password"