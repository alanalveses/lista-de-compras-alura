#Projeto Lista de Compras - Utilizado no Curso Objetos no JavaScript - Escola Front-End Alura

Neste arquivo encontram-se modelos de códigos que serão utilizados no decorrer do curso. 

Código modelo da li "Comprados":

    <li class="item-compra is-flex is-justify-content-space-between" data-value="">
        <div>
            <input type="checkbox" checked class="is-clickable" />  
            <span class="itens-comprados is-size-5"></span>
        </div>
        <div>
            <i class="fa-solid fa-trash is-clickable deletar"></i>
        </div>
    </li>

Código modelo da li "Lista de compras": 

    <li class="item-compra is-flex is-justify-content-space-between" data-value="">
        <div>
            <input type="checkbox" class="is-clickable" />
            <input type="text" class="is-size-5" value=""></input>
        </div>
        <div>
            <i class="fa-solid fa-trash is-clickable deletar"></i>
        </div>
    </li>

Input com código refatorado:

    <div>
        <input type="checkbox" checked class="is-clickable" />  
        <span class="itens-comprados is-size-5">${elemento.valor}</span>
    </div>

Ícones de edição:

    <i class="fa-regular fa-floppy-disk is-clickable"></i><i class="fa-regular is-clickable fa-pen-to-square editar"></i>

arrey
let listaCompras = ['Arroz', 'Feijão', 'Macarrão']

objeto
const listaItens = {
    item1: 'biscoito',
    item2: 'suco',
    quantidade1: 3,
    quantidade2: 4,
    mostrarItens: function() {
        alert('Comprei '+ listaItens.quantidade1 + ' pacotes de ' + listaItens.item1)
    }
}

listaItens.mostrarItens()

splice

        listaDeItens.splice(valorDoElemento,0,{valor: "Limão", checar: false})

        Índice de início (valorDoElemento): O primeiro parâmetro indica o índice a partir do qual a modificação será feita no array. Neste caso, é o valor de valorDoElemento, que representa a posição onde você quer fazer a alteração.
        
        Número de itens a remover: O segundo parâmetro indica quantos elementos devem ser removidos a partir do índice especificado. Se o valor for 0, nenhum item será removido, e o novo item será apenas inserido no índice fornecido.
        
        Itens a adicionar: O terceiro parâmetro (e os subsequentes, se houver) são os elementos que você deseja adicionar ao array a partir da posição indicada pelo primeiro parâmetro. No exemplo, {valor: "Limão", checar: false} é o objeto que será inserido no array.
        
        o 0 faz ele inserir um objeto, no caso o limão,
        o 1 faz ele substituir 1 objeto pelo 3 argumento
