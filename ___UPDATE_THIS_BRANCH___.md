cd <location to clone>
git fetch upstream

# Optional: preview what's new before merging
git log --oneline mmx-deployment..upstream/stable/1.18.x

git switch mmx-deployment
git merge upstream/stable/1.18.x
git push
