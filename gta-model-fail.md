## GTA:SA had trouble loading a model.

Model id: <span id="modelid"></span> (<span id="reason"></span>)

This could be due to one of these problems:
 1. **You have added custom models to GTA:SA which are incompatible with MTA**
     - Re-install GTA:SA.
     - Make sure the file 'gta3.img' is not modified.
 2. **The server you were connected to has custom models which are incompatible with MTA**
     - Ask the server owner to check if model id 15678 is customized.
 3. **Some other problem or bug in GTA:SA or MTA**
     - Oh no. 


<script>
const url = new URL(window.location);
const id = url.searchParams.get("id");
const reason = url.searchParams.get("reason");
document.getElementById("modelid").innerHTML = id;
document.getElementById("reason").innerHTML = reason;
</script>
