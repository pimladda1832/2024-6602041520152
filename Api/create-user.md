curl -X POST http://localhost:8080/api/auth/local/register \
     -H "Content-Type: application/json" \
     -H "Authorization: Bearer 097868fda2cd3cdb1be29960d2bf0e39977d489ed7372940bafb594029bd6cd9263ae7047962b372d67ca1c88672a92602aae551d265758bf0f519b6cd90021784d64dcb3c623c801d8ee88fe416fb9b223cfa81a42d4384828155a806bd275754d2493d81544b517b5aac5f7541955bc77a0d596bc9353cb93396d985c57adc" \
     -d '{
          "username": "P24",
          "email": "ppp2143@hotmail.com",
          "password": "P@2511"
     }'