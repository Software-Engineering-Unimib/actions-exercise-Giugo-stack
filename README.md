Dopo aver modificato la versione nel pom, la build mi dà comunque errore nel Dependency Graph, ho provato a risolverlo aggiungendo dei permessi -> permissions:
                                                                                                                                                    contents: read
                                                                                                                                                    dependency-graph: write
                                                                                                                                                    security-events: write
Nel maven.yml ma la build dà comunque errore perchè non sono "allowed".
