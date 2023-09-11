# Chroma_Vector_DB
<H2>Voorbeeld toepassing Vector Database met Chroma</H2>
<p>Kan je met Artificial Intelligence slim semantisch zoeken op je eigen actuele gegevens en documenten? Jazeker, door gebruik te maken van een Vector database (zoals Chroma of Weaviate ) en ChatGPT of een ander LLM.</p>

<p>Onderstaande afbeelding geeft de werking aan. In dit voorbeeld gebruik ik een bestand met 15620 meest gestelde vragen en antwoorden aan de overheid als voorbeeld. Ik laad alle teksten in de Chroma Vector database, die omgezet worden naar vectoren m.b.v. embedding technologie. Vervolgens kan ik een zoekopdracht geven. De Vector database geeft me de meest waarschijnlijke antwoorden, die ik vervolgens gebruikersvriendelijk ombouw met behulp van ChatGPT en prompt-engineering. Zo krijgt de vragensteller een keurig antwoord.</p>

<p>Deze aanpak heet officieel Retrieval Augmented Generation (RAG).</p>

<img src="Sematic_search_ChromaDB.jpg"></p>
