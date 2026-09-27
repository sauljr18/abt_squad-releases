# abt — binários de release

Repositório **público** só de binários compilados do `abt` (SPEC GAP-001): permite
`abt version --check` e `abt update` sem credencial. **Nenhum código-fonte aqui.**

Cada release traz:
- `abt-linux-amd64` e `abt-windows-amd64.exe`
- `checksums.txt` (SHA-256 de cada binário), conferido pelo `abt update` antes de substituir
- notas do release, exibidas pelo `abt update` como "o que mudou"

Canal único no v1: `stable`.
