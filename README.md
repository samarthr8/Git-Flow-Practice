				
				################################ GitHub - GitFlow    ######################################

1. Login to GitHub, create a new repository.
2. Clone the repository to your local machine/ec2 machine. 
3. Install and initialise git flow - 
			sudo apt-get update
			sudo apt-get install git-flow -y
			git flow init -d
4. git push origin
5. git push --set-upstream origin develop

6. git flow feature start feature1
7. touch feature1.html
8. git add .
9. git commit -m "Feature1.html added"
10. git flow feature finish feature1

11. git push origin
12. git flow release start "0.1.0"
13. git push origin
14. git push --set-upstream origin release/0.1.0
15. touch release-fix.html
16. git add .
17. git commit -m "release fixed" 
18. git push origin
19. git flow release finish "0.1.0"

20. git checkout main
21. git push origin
22. git push origin 0.1.0
23. git checkout develop
24. git push origin

