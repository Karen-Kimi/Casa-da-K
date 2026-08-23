# Core Template — Reserva v0.1

Este pacote é uma **base funcional genérica** derivada da linhagem estável da Casa Digital, preparada para ser clonada em outros projetos sem carregar o conteúdo pessoal da Casa.

## Comece por aqui

1. Abra `core-template.html` no celular ou desktop.
2. Edite `CORE_TEMPLATE_CONFIG` no início do JavaScript para trocar nome e cômodos.
3. Mantenha os contratos de storage, Registry, Bridge e Biblioteca enquanto troca interface e módulos.
4. Para ferramentas independentes, use `tool-template-bridge03.html` como molde e teste pela Doca.

## O que já existe

- App Shell mobile-first;
- Hash Router;
- Room Hub gerado por configuração;
- Module Registry com módulo multi-cômodo;
- IndexedDB + fallback localStorage;
- Records compartilhados;
- Quick Capture;
- Busca;
- Favoritos;
- Importador JSON/TXT em blocos;
- Biblioteca/Acervo;
- Matéria-prima compartilhada por cômodo/Casa;
- Doca de HTML/URL;
- Alfândega + Bridge 0.3;
- persistência de estado de ferramenta atracada;
- registro de ferramenta externa com “porta” no cômodo;
- Debug/Trace;
- exemplo de módulo nativo;
- exemplo de módulo compartilhado entre dois cômodos.

## O que NÃO é obrigatório manter

Os nomes dos cômodos, cores, textos, módulos de exemplo e estética são substituíveis.

## O que deve ser tratado como contrato

- IDs estáveis;
- Registry/manifesto;
- lifecycle/mount/cleanup;
- storage por API, não acesso acoplado;
- registros com schema/version quando necessário;
- Bridge/Alfândega para ferramenta móvel;
- diferença entre Matéria-prima e Biblioteca/Acervo;
- import/export e genealogia/migração;
- Debug de fronteira sem conteúdo sensível por padrão.

## Linhagem

`Core Template Reserva v0.1` é uma linha paralela de referência. Não substitui nem incrementa a numeração da Casa Digital.
