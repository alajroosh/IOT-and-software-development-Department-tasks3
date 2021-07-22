# IOT-and-software-development-Department-tasks3
IOT-and-software-development-Department-tasks3
<br/>
in this task we have IBM waston assistant.
<br/>
after i registered in the IBM website 
<br/>
i Create new assistant
<br/>
![image](https://user-images.githubusercontent.com/23351217/126528587-470ef1a3-7127-4e80-9e7b-e3a58e385ebb.png)
<br/>
then i Create a skills for the  assistant’s
<br/>
![image](https://user-images.githubusercontent.com/23351217/126581798-5bf17aad-6579-4d27-ae48-593dedc57d8d.png)
<br/>
after finsh i download json file and i use integrations tool to make the web chat
<br/>
![image](https://user-images.githubusercontent.com/23351217/126582857-ea3e36a2-eaf9-4956-befb-ba0f33da60d3.png)
<br/>
![image](https://user-images.githubusercontent.com/23351217/126582111-8f0146a4-edf8-4330-bee3-5fb25990df84.png)
<br/>
this the javascribt code 
<br/>

```ruby
  <script>
  window.watsonAssistantChatOptions = {
      integrationID: "53bafea4-cd9f-46ff-8983-92db011deae2", // The ID of this integration.
      region: "eu-de", // The region your integration is hosted in.
      serviceInstanceID: "3fc5759e-8e91-4487-a2a8-53bc8822e5b9", // The ID of your service instance.
      onLoad: function(instance) { instance.render(); }
    };
  setTimeout(function(){
    const t=document.createElement('script');
    t.src="https://web-chat.global.assistant.watson.appdomain.cloud/loadWatsonAssistantChat.js";
    document.head.appendChild(t);
  });
</script>
```
<br/>
i use this code in my html page
<br/>

![image](https://user-images.githubusercontent.com/23351217/126582585-bf4634fb-62ad-4cbe-881d-f38a7f719ef1.png)
<br/>

![image](https://user-images.githubusercontent.com/23351217/126582613-3d236dbd-3950-473d-bfb8-a4e406d12afe.png)

