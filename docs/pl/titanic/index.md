# Exploracyjna Analiza Danych (EDA) Titanica:

Przedstawiam swój projekt, który łączy historię Titanica z danymi o przeżywalności pasażerów, informacjami dotyczącymi budowy statku, rozmieszczenia szalup ratunkowych, itp. Dzięki ciekawym ilustracjom i opisom, projekt ten czyta się jak dobry kryminał, który przeniesie Cię na pokład Titanica niemal pozwalając poczuć atmosferę tamtych dni. Zapraszam do zanurzenia się w świat tej fascynującej opowieści.

<a href="titanic_rafal_ney.ipynb" class="md-button md-button--primary">Pobierz Notebook</a>

<iframe
    id="content"
    src="titanic_rafal_ney.html"
    width="100%"
    style="border:1px solid black;overflow:hidden;"
></iframe>
<script>
function resizeIframeToFitContent(iframe) {
    iframe.style.height = (iframe.contentWindow.document.documentElement.scrollHeight + 50) + "px";
    iframe.contentDocument.body.style["overflow"] = 'hidden';
}
window.addEventListener('load', function() {
    var iframe = document.getElementById('content');
    resizeIframeToFitContent(iframe);
});
window.addEventListener('resize', function() {
    var iframe = document.getElementById('content');
    resizeIframeToFitContent(iframe);
});
</script>
