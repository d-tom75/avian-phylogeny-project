# avian-phylogeny-project
This is a project for CS 466 (Introduction to Bioinformatics) where we seek to illustrate the divergence between paleognaths and neognaths through the RAG1 gene via hierarchical clustering algorithms.

## Motivation
Various birds have evolved over time to take on different traits. We wanted to investigate what makes flightless birds differ from birds that fly. Birds, which form class Aves, are split into two infraclasses. The first of these are paleognaths, which include the ratites, which consists of four flightless orders including birds such as ostriches, emus, kiwis, and cassowaries, as well as tinamous, which can fly but are poor at it. The other are neognaths, consisting of all other birds, the majority of which are able to fly proficiently. One gene that will be helpful to classify these species is the RAG1 (Recombination Activating Gene 1) gene. The literature has shown this gene to provide a strong base to find relationships along the paleognaths and their split with the neognaths. In order to truly visualize the genetic differences between flightless and non-flightless birds, we will implement a hierarchical clustering algorithm such as Neighbor-Joining or UPGMA on collected RAG1 data which will hopefully display 2 subtrees: one with all paleognath bird species and one with all neognath bird species.

## Data
We have collected RAG1 sequences for bird species from a variety of taxonomic orders and families in class Aves from the NIH's NCBI dataset. Below are the 30 species that are a part of our dataset:

Infraclass Palaeognathae:
+ *Apteryx mantelli* (North Island brown kiwi)
+ *Apteryx rowi* (Okarito brown kiwi)
+ *Dromaius novaehollandiae* (Emu)
+ *Nothoprocta perdicaria* (Chilean tinamou)
+ *Rhea pennata* (Darwin's rhea)
+ *Struthio camelus* (African ostrich)
+ *Tinamus guttatus* (White-throated tinamou)

Infraclass Neognathae:
+ *Anas platyrhynchos* (Mallard)
+ *Aphelocoma coerulescens* (Florida scrub jay)
+ *Aptenodytes forsteri* (Emperor penguin)
+ *Athene cunicularia* (Burrowing owl)
+ *Balearica regulorum gibbericeps* (East African grey crowned crane)
+ *Calonectris borealis* (Cory's shearwater)
+ *Cariama cristata* (Red-legged seriema)
+ *Catharus ustulatus* (Swainson's thrush)
+ *Columba livia* (Rock pigeon)
+ *Corvus moneduloides* (New Caledonian crow)
+ *Cygnus olor* (Mute swan)
+ *Dryobates pubescens* (Downy woodpecker)
+ *Eurypyga helias* (Sunbittern)
+ *Falco naumanni* (Lesser kestrel)
+ *Haliaeetus leucocephalus* (Bald eagle)
+ *Hirundo rustica* (Barn swallow)
+ *Larus michahellis* (Yellow-legged gull)
+ *Lathamus discolor* (Swift parrot)
+ *Merops nubicus* (Northern carmine bee-eater)
+ *Phalacrocorax carbo* (Great cormorant)
+ *Pygoscelis adeliae* (Adélie penguin)
+ *Strigops habroptila* (Kakapo)
+ *Tauraco erythrolophus* (Red-crested turaco)