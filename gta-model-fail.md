
##GTA:SA had trouble loading a model.

That's sad.

Model id: <span id="modelid"></span> (<span id="reason"></span>

<script>
const url = new URL(window.location);
const id = url.searchParams.get("id");
const reason = url.searchParams.get("reason");
document.getElementById("modelid").innerHTML = id;
document.getElementById("reason").innerHTML = reason;
</script>
