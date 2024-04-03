# my-titan-takeoff
```
helm install titan-takeoff . --set modelName=google/flan-t5-small --set gpu=true

# In windows Anaconda shell
curl -k -X POST -H "Content-type:application/json" -N -d "{\"text\": \"Hello world!\"}"  https://titan-takeoff.83-206-89-106.nip.io/generate_stream
```
