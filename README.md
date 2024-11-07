
mkdir <repo>
cd <repo>
gitd init

gitd remote add origin gnfd://greenfield-chain-ap.bnbchain.org:443/codex-${user-id}-${repo-name}
echo "Hello CodexField" >> README.md
gitd add README.md
gitd commit -m "add README.md"
gitd push origin main -f|

cd <new_folder>
gitd clone gnfd://greenfield-chain-ap.bnbchain.org:443/codex-${user-id}-${repo-name}
