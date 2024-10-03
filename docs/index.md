<h2><a href= "https://www.mackenzie.br">Universidade Presbiteriana Mackenzie</a></h2>
<h3><a href= "https://www.mackenzie.br/graduacao/sao-paulo-higienopolis/sistemas-de-informacao">Sistemas de Informação</a></h3>


<font size="+12"><center>
*&lt;Nome do Projeto&gt;*
</center></font>

>*Observação 1: A estrutura inicial deste documento é só um exemplo. O seu grupo deverá alterar esta estrutura de acordo com o que está sendo solicitado na disciplina.*

>*Observação 2: O índice abaixo não precisa ser editado se você utilizar o Visual Studio Code com a extensão **Markdown All in One**. Essa extensão atualiza o índice automaticamente quando o arquivo é salvo.*

**Conteúdo**

- [Autores](#nome-alunos)
- [Descrição do Projeto](#introdução-do-projeto)
- [Análise de Requisitos Funcionais e Não-Fucionais](#descrição-dos-requisitos)
- [Diagrama de Atividades](#diagrama-de-atividades) 
- [Diagrama de Casos de Uso](#diagrama-de-comportamento-atores)
- [Descrição dos Casos de Uso](#descrição-das-funcões)
- [Diagrama de Senquencia](#diagrama-de-ordem-interações)
- [Diagrama de Classes](#diagrama-orientado-objetos)
- [Diagrama de Estados](#diagrama-estrutura-componente)
- [Diagrama de Implantação](#diagrama-de-hardware-software)
- [Referências](#referências)


# Autores

* Beatriz Soares
* Bruna Zakaib Pessoa
* Isabela Reali
* Mariana Chiorboli
* Yasmin Mendes



# Descrição do Projeto

*&lt;Introdução do projeto&gt;*

# Análise de Requisitos Funcionais e Não-Funcionais
## Requisitos Funcionais
* Gestão de Pedidos:
Receber pedidos da loja central;
Confirmar o recebimento do pedido pela pizzaria;
Atualizar o status do pedido em tempo real (preparo, saída para entrega, entregue).
* Localização e Roteamento:
Localizar a pizzaria mais próxima do cliente;
Calcular o trajeto mais curto e rápido para a entrega;
Monitorar a localização do entregador em tempo real.
* Controle de Tempo:
Controlar o tempo de preparo da pizza;
Controlar o tempo de saída da pizzaria até a casa do cliente;
Garantir que a entrega seja feita em menos de 30 minutos.
* Comunicação:
Notificar o cliente sobre o status do pedido (pedido recebido, em preparo, a caminho, entregue);
Permitir comunicação direta entre o cliente e o entregador.
* Suporte ao Cliente:
Oferecer suporte ao cliente via chat ou telefone;
Registrar e gerenciar reclamações e feedbacks dos clientes.
* Segurança de Dados:
Proteger os dados pessoais dos clientes;
Garantir a conformidade com as leis de proteção de dados.

## Requisitos Não-Funcionais
* Desempenho:
O sistema deve ser capaz de processar e atualizar o status dos pedidos em tempo real;
O tempo de resposta do sistema deve ser inferior a 2 segundos para qualquer operação.
* Escalabilidade:
O sistema deve suportar um aumento no número de pedidos sem degradação de desempenho;
Deve ser possível adicionar novas pizzarias ao sistema sem necessidade de grandes modificações.
* Usabilidade:
A interface do sistema deve ser intuitiva e fácil de usar para os funcionários das pizzarias e entregadores;
Deve haver treinamento e documentação disponíveis para os usuários do sistema.
* Manutenibilidade:
O sistema deve ser modular para facilitar a manutenção e atualização;
Deve haver logs detalhados para monitoramento e diagnóstico de problemas.
* Notificações e Alertas:
Enviar notificações e alertas para os gerentes em caso de atrasos ou problemas na entrega.

# Diagrama de Atividades
[Uploading Diagrama de a<mxfile host="app.diagrams.net" agent="Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/129.0.0.0 Safari/537.36" version="24.7.16">
  <diagram name="Página-1" id="D6T-ny9HFWSgQPYE0R1I">
    <mxGraphModel grid="1" page="1" gridSize="10" guides="1" tooltips="1" connect="1" arrows="1" fold="1" pageScale="1" pageWidth="827" pageHeight="1169" math="0" shadow="0">
      <root>
        <mxCell id="0" />
        <mxCell id="1" parent="0" />
        <mxCell id="2Vbqry-GRGLUIXmraaCw-1" value="CLIENTE" style="swimlane;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="70" y="130" width="260" height="610" as="geometry" />
        </mxCell>
        <mxCell id="2Vbqry-GRGLUIXmraaCw-3" value="" style="ellipse;whiteSpace=wrap;html=1;" vertex="1" parent="2Vbqry-GRGLUIXmraaCw-1">
          <mxGeometry x="100" y="50" width="50" height="40" as="geometry" />
        </mxCell>
        <mxCell id="2Vbqry-GRGLUIXmraaCw-5" value="Fazer o pedido" style="rounded=0;whiteSpace=wrap;html=1;" vertex="1" parent="2Vbqry-GRGLUIXmraaCw-1">
          <mxGeometry x="60" y="120" width="130" height="50" as="geometry" />
        </mxCell>
        <mxCell id="2Vbqry-GRGLUIXmraaCw-4" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;" edge="1" parent="2Vbqry-GRGLUIXmraaCw-1" source="2Vbqry-GRGLUIXmraaCw-3" target="2Vbqry-GRGLUIXmraaCw-5">
          <mxGeometry relative="1" as="geometry">
            <mxPoint x="125" y="130" as="targetPoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="2Vbqry-GRGLUIXmraaCw-6" value="SISTEMA&amp;nbsp;" style="swimlane;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="370" y="130" width="260" height="610" as="geometry" />
        </mxCell>
        <mxCell id="2Vbqry-GRGLUIXmraaCw-12" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;entryX=0.5;entryY=0;entryDx=0;entryDy=0;" edge="1" parent="2Vbqry-GRGLUIXmraaCw-6" source="2Vbqry-GRGLUIXmraaCw-8" target="2Vbqry-GRGLUIXmraaCw-11">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="2Vbqry-GRGLUIXmraaCw-8" value="Localizar a Pizzaria mais próxima do cliente" style="rounded=0;whiteSpace=wrap;html=1;" vertex="1" parent="2Vbqry-GRGLUIXmraaCw-6">
          <mxGeometry x="44" y="80" width="150" height="90" as="geometry" />
        </mxCell>
        <mxCell id="2Vbqry-GRGLUIXmraaCw-11" value="Mandar o pedido para a Pizzaria" style="rounded=0;whiteSpace=wrap;html=1;" vertex="1" parent="2Vbqry-GRGLUIXmraaCw-6">
          <mxGeometry x="44" y="240" width="150" height="90" as="geometry" />
        </mxCell>
        <mxCell id="2Vbqry-GRGLUIXmraaCw-13" value="PIZZARIA" style="swimlane;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="680" y="130" width="260" height="610" as="geometry" />
        </mxCell>
        <mxCell id="2Vbqry-GRGLUIXmraaCw-14" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;entryX=0.5;entryY=0;entryDx=0;entryDy=0;" edge="1" parent="2Vbqry-GRGLUIXmraaCw-13" source="2Vbqry-GRGLUIXmraaCw-15" target="2Vbqry-GRGLUIXmraaCw-16">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="2Vbqry-GRGLUIXmraaCw-15" value="Recebe o pedido do sistema" style="rounded=0;whiteSpace=wrap;html=1;" vertex="1" parent="2Vbqry-GRGLUIXmraaCw-13">
          <mxGeometry x="50" y="80" width="150" height="90" as="geometry" />
        </mxCell>
        <mxCell id="2Vbqry-GRGLUIXmraaCw-17" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;" edge="1" parent="2Vbqry-GRGLUIXmraaCw-13" source="2Vbqry-GRGLUIXmraaCw-16">
          <mxGeometry relative="1" as="geometry">
            <mxPoint x="125" y="370" as="targetPoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="2Vbqry-GRGLUIXmraaCw-16" value="Cozinha e embala a pizza para entrega" style="rounded=0;whiteSpace=wrap;html=1;" vertex="1" parent="2Vbqry-GRGLUIXmraaCw-13">
          <mxGeometry x="50" y="220" width="150" height="90" as="geometry" />
        </mxCell>
        <mxCell id="2Vbqry-GRGLUIXmraaCw-20" value="" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;" edge="1" parent="2Vbqry-GRGLUIXmraaCw-13" source="2Vbqry-GRGLUIXmraaCw-18" target="2Vbqry-GRGLUIXmraaCw-19">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="2Vbqry-GRGLUIXmraaCw-18" value="Chama o motoboy" style="rounded=0;whiteSpace=wrap;html=1;" vertex="1" parent="2Vbqry-GRGLUIXmraaCw-13">
          <mxGeometry x="50" y="364.5" width="150" height="90" as="geometry" />
        </mxCell>
        <mxCell id="2Vbqry-GRGLUIXmraaCw-19" value="Entrega a pizza" style="rounded=0;whiteSpace=wrap;html=1;" vertex="1" parent="2Vbqry-GRGLUIXmraaCw-13">
          <mxGeometry x="55" y="500" width="140" height="80" as="geometry" />
        </mxCell>
        <mxCell id="2Vbqry-GRGLUIXmraaCw-21" value="MOTOBOY" style="swimlane;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="1000" y="130" width="260" height="610" as="geometry" />
        </mxCell>
        <mxCell id="2Vbqry-GRGLUIXmraaCw-22" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;entryX=0.5;entryY=0;entryDx=0;entryDy=0;" edge="1" parent="2Vbqry-GRGLUIXmraaCw-21" source="2Vbqry-GRGLUIXmraaCw-23" target="2Vbqry-GRGLUIXmraaCw-25">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="2Vbqry-GRGLUIXmraaCw-23" value="Recebe a pizza" style="rounded=0;whiteSpace=wrap;html=1;" vertex="1" parent="2Vbqry-GRGLUIXmraaCw-21">
          <mxGeometry x="50" y="80" width="150" height="90" as="geometry" />
        </mxCell>
        <mxCell id="2Vbqry-GRGLUIXmraaCw-24" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;" edge="1" parent="2Vbqry-GRGLUIXmraaCw-21" source="2Vbqry-GRGLUIXmraaCw-25">
          <mxGeometry relative="1" as="geometry">
            <mxPoint x="125" y="370" as="targetPoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="2Vbqry-GRGLUIXmraaCw-25" value="Leva a pizza ao cliente" style="rounded=0;whiteSpace=wrap;html=1;" vertex="1" parent="2Vbqry-GRGLUIXmraaCw-21">
          <mxGeometry x="50" y="220" width="150" height="90" as="geometry" />
        </mxCell>
        <mxCell id="2Vbqry-GRGLUIXmraaCw-26" value="" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;" edge="1" parent="2Vbqry-GRGLUIXmraaCw-21" source="2Vbqry-GRGLUIXmraaCw-27" target="2Vbqry-GRGLUIXmraaCw-28">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="2Vbqry-GRGLUIXmraaCw-27" value="Entrega a Pizza" style="rounded=0;whiteSpace=wrap;html=1;" vertex="1" parent="2Vbqry-GRGLUIXmraaCw-21">
          <mxGeometry x="50" y="364.5" width="150" height="90" as="geometry" />
        </mxCell>
        <mxCell id="2Vbqry-GRGLUIXmraaCw-28" value="Finaliza o pedido" style="rounded=0;whiteSpace=wrap;html=1;" vertex="1" parent="2Vbqry-GRGLUIXmraaCw-21">
          <mxGeometry x="55" y="500" width="140" height="80" as="geometry" />
        </mxCell>
        <mxCell id="chHtD0AbRH1xzWBRown5-1" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;entryX=0;entryY=0.75;entryDx=0;entryDy=0;" edge="1" parent="1" source="2Vbqry-GRGLUIXmraaCw-5" target="2Vbqry-GRGLUIXmraaCw-8">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="chHtD0AbRH1xzWBRown5-2" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;entryX=0;entryY=0.5;entryDx=0;entryDy=0;" edge="1" parent="1" source="2Vbqry-GRGLUIXmraaCw-11" target="2Vbqry-GRGLUIXmraaCw-15">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="chHtD0AbRH1xzWBRown5-3" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;entryX=0;entryY=0.5;entryDx=0;entryDy=0;" edge="1" parent="1" source="2Vbqry-GRGLUIXmraaCw-19" target="2Vbqry-GRGLUIXmraaCw-23">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
      </root>
    </mxGraphModel>
  </diagram>
</mxfile>
tividade.drawio…]()



# Diagrama de Casos de Uso

*&lt;Diagrama para visualizar o comportamento dos atores&gt;*

# Descrição dos Casos de Uso

*&lt;Descrição do comportamento entre os atores/resquisitos&gt;*

# Diagrama de Sequência

*&lt;Diagrama de ordem e interação dos objetos&gt;*

# Diagrama de Classes

*&lt;Diagrama de relacionamento entre classes para os seus atributos e operações&gt;*

# Diagrama de Estados

*&lt;Diagrama para permite modelar o comportamento interno de um determinado objeto, subsistema ou sistema global&gt;*

# Diagrama de Implantação

*&lt;Diagrama para exibir o relacionamento de hardware e software no projeto&gt;*

# Referências

*&lt;Lista de referências&gt;*
