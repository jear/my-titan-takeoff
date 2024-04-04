# my-titan-takeoff
```
helm install titan-takeoff . --set modelName=google/flan-t5-small --set gpu=true

# In windows Anaconda shell
curl -k -X POST -H "Content-type:application/json" -N -d "{\"text\": \"Hello world!\"}"  https://titan-takeoff.83-206-89-106.nip.io/generate_stream

curl   -H "Content-Type: application/json"   -d "{\"prompt\": \"This is a cake recipe:\n\n1.\", \"max_tokens\": 200, \"temperature\": 1, \"top_p\": 0.9, \"seed\": 10  }" https://gradio2-api.83-206-89-105.nip.io/v1/completions
```
