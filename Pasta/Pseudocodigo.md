```text
INICIO Algoritmo PullRequest

    desenvolver_funcionalidade()
    criar_branch()
    fazer_commit()
    fazer_push()
    abrir_pull_request()

    aprovado <- verificar_aprovacao()

    ENQUANTO (aprovado == FALSO) FACA
        fazer_ajustes()
        fazer_commit()
        atualizar_pull_request()
        aprovado <- verificar_aprovacao()
    FIM ENQUANTO

    realizar_merge()
    exibir_mensagem("Pull Request aprovado e merge realizado")

FIM Algoritmo
