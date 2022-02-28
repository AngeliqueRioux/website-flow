# website-flow
remote test github pour merge
Fromage à pizza que je préfère:
    mozzarella
    gruyere
    chevre
    curé nantais


Eleve4@POST000154428 MINGW64 ~/website-flow (cheese)
$ git pull origin cheese
Enter passphrase for key '/c/Users/Eleve4/.ssh/id_ed25519': 
fatal: couldn't find remote ref cheese

Eleve4@POST000154428 MINGW64 ~/website-flow (cheese)
On branch cheese
nothing to commit, working tree clean

Eleve4@POST000154428 MINGW64 ~/website-flow (cheese)
$ git add *

Eleve4@POST000154428 MINGW64 ~/website-flow (cheese)
$ git commit -m 'test'
On branch cheese
nothing to commit, working tree clean

Eleve4@POST000154428 MINGW64 ~/website-flow (cheese)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Eleve4@POST000154428 MINGW64 ~/website-flow (main)
$ git pull origin main
Enter passphrase for key '/c/Users/Eleve4/.ssh/id_ed25519':
remote: Enumerating objects: 8, done.
remote: Counting objects: 100% (8/8), done.
remote: Compressing objects: 100% (3/3), done.
Unpacking objects: 100% (4/4), 1.32 KiB | 58.00 KiB/s, done.
remote: Total 4 (delta 0), reused 0 (delta 0), pack-reused 0
From github.com:AngeliqueRioux/website-flow
 * branch            main       -> FETCH_HEAD
   4986d43..8832f9d  main       -> origin/main
Updating 4986d43..8832f9d
Fast-forward
 README.md | 8 +++++++-
 1 file changed, 7 insertions(+), 1 deletion(-)

Eleve4@POST000154428 MINGW64 ~/website-flow (main)
$ git add *

Eleve4@POST000154428 MINGW64 ~/website-flow (main)
$ git commit -m 'modification readme'
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

Eleve4@POST000154428 MINGW64 ~/website-flow (main)
$ git push origin main
Enter passphrase for key '/c/Users/Eleve4/.ssh/id_ed25519': 
To github.com:AngeliqueRioux/website-flow.git
 ! [rejected]        main -> main (fetch first)
error: failed to push some refs to 'github.com:AngeliqueRioux/website-flow.git'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

Eleve4@POST000154428 MINGW64 ~/website-flow (main)
$ git push --help

Eleve4@POST000154428 MINGW64 ~/website-flow (main)
$ git merge
Already up to date.

Eleve4@POST000154428 MINGW64 ~/website-flow (main)
$ git pull origin main
Enter passphrase for key '/c/Users/Eleve4/.ssh/id_ed25519': 
remote: Enumerating objects: 5, done.
remote: Counting objects: 100% (5/5), done.
remote: Compressing objects: 100% (2/2), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), 740 bytes | 38.00 KiB/s, done.
From github.com:AngeliqueRioux/website-flow
 * branch            main       -> FETCH_HEAD
   8832f9d..09eb747  main       -> origin/main
Updating 8832f9d..09eb747
Fast-forward
 README.md | 2 +-
 1 file changed, 1 insertion(+), 1 deletion(-)

Eleve4@POST000154428 MINGW64 ~/website-flow (main)
$ git add *

Eleve4@POST000154428 MINGW64 ~/website-flow (main)
$ git commit -m 'essai merge'
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

Eleve4@POST000154428 MINGW64 ~/website-flow (main)
$ git push
Enter passphrase for key '/c/Users/Eleve4/.ssh/id_ed25519':
Everything up-to-date

Eleve4@POST000154428 MINGW64 ~/website-flow (main)
$ git add *

Eleve4@POST000154428 MINGW64 ~/website-flow (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

Eleve4@POST000154428 MINGW64 ~/website-flow (main)
$ git pull origin main
Enter passphrase for key '/c/Users/Eleve4/.ssh/id_ed25519': 
From github.com:AngeliqueRioux/website-flow
 * branch            main       -> FETCH_HEAD
Already up to date.

Eleve4@POST000154428 MINGW64 ~/website-flow (main)