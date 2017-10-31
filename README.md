# Solemne 2

### Por José Miguel Yañez Mena

## Parte I: Metagenómica, metatranscriptóma y microbioma humano.

1. Usted trabaja como asistente de investigacion en el Centro de Bioinformatica y Biologia Integrativa de la Universidad Andres Bello. Su jefe le asigna un proyecto de alta prioridad: se le indica que, en el refrigerador (a -20 °C), usted encontrará un tubo eppendorf que contiene ADN aislado desde una muestra fecal proveniente de un paciente, cuya identidad desconoce (no es importante). El paciente presenta claros sintomas de una infeccion bacteriana intestinal, pero no se ha podido identificar la identidad del patógeno responsable mediante el metodo tradicional de cultivo en placa de Petri. Disponiendo usted de una muestra de ADN total aislado de una muestra de heces del paciente, describa de forma breve y precisa su plan de trabajo, paso a paso, para responder a la siguiente pregunta: ¿Que bacterias estan presentes en la muestra?

* R: Primeramente, realizaria un amplicon sequencing usando un primer ubicuo para el rRNA 16S, el cual se encuentra en cada bacteria y es altamente conservado. Luego usaria los resultados analíticos obtenidos para hacer una comparacion taxonómica y filogenética con lo que se puede encontrar en las bases de datos metagenómicos. 

2. Usted ya tiene los resultados de su trabajo, es decir, usted sabe qué bacterias estan presentes en la muestra. De acuerdo a sus hallazgos, ¿bajo que criterio usted indicaria a una de las bacterias como el patogeno y por qué?

* R: Gracias a la comparacion anterior sabemos cuales bacterias han sido reportadas como patógenas y cuales son parte de la microbiota normal. Ahora bien, me enfocaria en el grupo de bacterias patógenas y revisaria en las bases de datos cual de estas produce los sintomas presentes en el paciente de donde se saco la muestra. En el hipotetico caso de que mas de una bacteria coincida con estos sintomas realizaria un shotgun sequencing de la muestra de adn total, ya que esta tecnica tiene la capacidad de entregar la abundancia del microorganismo en un determinado medio. De esta manera, la bacteria patógena que estuviera en mayor abundancia podria ser señalada como la causante de la enfermedad.

## Parte II: Proteínas y evolucion

Caracterice evolutivamente proteínas de la familia de isoprenyl synthetase (mínimo 5 proteinas distintas) determinando si: ¿existe una relacion convergente o divergente entre ellas? y ¿porque?. Utilice bases de datos como: Uniprot, Prosite, Pfam, entre otras.

R: Las proteinas elegidas (con su respectivo codigo Uniprot) de esta basta familia fueron: 

- Octaprenyl-diphosphate synthase (M5DUQ3) del organismo Thalassolituus oleivorans MIL-1
- Solanesyl diphosphate synthase (Q8DI35) del organismo Thermosynechococcus elongatus (strain BP-1)
- Polyprenyl synthetase (A9AYK7) del organismo Herpetosiphon aurantiacus (strain ATCC 23779 / DSM 785)
- Trans-hexaprenyltranstransferase (G8TB06) del organismo Niastella koreensis (strain DSM 17620 / KACC 11465 / GR20-10)
- Solanesyl diphosphate synthase (K9R9G3) del organismo Rivularia sp. PCC 7116

Primeramente procedí a alinearlas en Uniprot. Obteniendo el siguiente resultado:

El árbol filogenético, donde se corrobora que todas provienen de bacterias.

![imagen alineamiento](https://github.com/Peepcross/ENSOLEMNA2/blob/master/alinean2.png)












