# Robot Framework

### Comandos terminal
`robot .\amazon_testes.robot` executa a suíte de teste;  
`robot -t "Caso de Teste 02 - Pesquisa de um Produto" amazon_testes.robot` executa apenas o caso de teste 02;  
`robot -d log .\amazon_testes.robot` executa os testes e salva os arquivos de saída na pasta `log`;  
`robot -d log -i menus .\amazon_testes_gherkin_bdd.robot` executa os testes com a tag `menu`;  
`robot -d log -e menus .\amazon_testes_gherkin_bdd.robot` executa todos os testes, menos os com a tag `menu`;  