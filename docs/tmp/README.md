Hello

<link rel="stylesheet" href="/test/docs/techno.css">

<script language="JavaScript">
function explanation (id) {
    document.getElementById(id).style.display="block"; 
}
</script>

<button type="button" onclick="javascript:explanation('xxx')" class="explanationbutton">Обяснения <span class="switch-label" data-on="On" data-off="Off"></span></button><br>
<div id="xxx" style="display:none">
bla bla bla
</div>
