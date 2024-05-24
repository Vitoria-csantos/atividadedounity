# atividadedounity
Esta pasta terá explicações de criação de uma cena no Unity.

<h1>Descrição da cena</h1>
<p>A cena é consideravelmente pequena mas com vários elementos presentes, no centro há um poço antigo cercado por um jardim com diversas árvores (uma delas sendo uma macieira), plantas (como grama, flores, cogumelos) e pedras sem esquecer claro do caminho de pedras que da entrada ao local.</p>

<h2>Objects 3D</h2>
<p>São objetos 3D com formas simples criados pelo próprio programa, ou seja, não são oriundos da asset store ou de um asset original feito pelo desenvolvedor. Eles são acessados da seguinte forma: </p>
<p>Create > Object 3D > Selecionar a forma</p>

<h2>Material</h2>
<p>Material é a definição acerca de como uma superfície de um objeto 3D deve ser exibida. Ela pode ser acessada da seguinte forma:</p>
<p>Assets > Create > Material</p>
<p>Após adicionar o material, deve-se atribuir as características do material como a cor/estampa, efeito metálico e a suavidade. No caso da cena, o material foi usado na esfera criada pelo Objects 3D para simular uma maçã.</p>

<h2>Física na cena</h2>
<h3>Rigidbody</h3>
<p>Traduzindo, "rigidbody" significa "corpo rígido", ou seja, adiciona gravidade a um objeto, fazendo que, quando a cena comece, ele se mova de acordo com a sua posição. Caso aplicado no chão, ele cai. Na cena feita, ele está aplicado na maçã, fazendo com que ela caia da árvore.</p>
<h3>Physics material</h3>
<p>Ele ajusta os efeitos de fricção e ressalto de objetos em colisão, sendo usado para definir coisas como se o objeto que cair vai quicar, ou se arrastar, por exemplo. O physics material é acessado da seguinte forma:</p>
<p>Assets > Create > Physics Material</p>
<p>Após ser aplicado, basta arrastá-lo para o objeto onde deseja aplicar o physics material. Na cena, foi aplicado na maçã e no chão para que a fruta não escorregasse e quicasse.</p>

<h2>Fontes</h2>
<p>https://docs.unity3d.com/Manual/class-PhysicMaterial.html</p>
<p>https://docs.unity3d.com/ScriptReference/Rigidbody.html</p>
<p>https://docs.unity3d.com/510/Documentation/Manual/PrimitiveObjects.html</p>
