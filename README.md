## Hi there :)

I like making games and much more because of the fact that I'm always experimenting with new stuff and projects


[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=rdalx42)](https://github.com/anuraghazra/github-readme-stats)

```bash
# 1. Navigate to your projects folder
cd ~/Projects/

# 2. Find all Git repositories
find . -name ".git" -type d | while read repo; do
  echo "Repository: $(dirname "$repo")"
  cd "$(dirname "$repo")"
  git ls-files | xargs wc -l
  cd - > /dev/null
done
