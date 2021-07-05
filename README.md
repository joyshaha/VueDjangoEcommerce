# VueDjangoEcommerce
	At the beginning, clone the repository and navigate the root project folder from terminal, 
	you will get two separate folder for backend-django(vue_django_ecommerce) and frontent-vue.js(vue_ecommerce)  
	
# Setting up the environment(Django)

	Create a virtual environment using python:
		access project directory using terminal, go to vue_django_ecommerce, run below command in backend project directory
			* cd vue_django_ecommerce
			* python3 -m venv env
	After creating an environment run these commands on terminal in same directory to activate environment:
		* if linux:
			source env/bin/activate
		* if windows:
			env\Scripts\activate
	Run the below command after activation environment:
		* pip install -r requirements.txt
		* python manage.py makemigations
		* python manage.py migrate
		* python manage.py create superuser
		* python manage.py runserver
		
		
# Setting up(Vue)

	Normalization for every project:
	
		Auto:
			## Project setup
			```
			npm install
			```

			### Compiles and hot-reloads for development
			```
			npm run serve
			```

			### Compiles and minifies for production
			```
			npm run build
			```

			### Customize configuration
			See [Configuration Reference](https://cli.vuejs.org/config/).
	
		Manual:
			To initialize vue.js 
				* npm install -g @vue/cli (if didn't run yet, must apply to run any vue.js)
			To create new project of vue manually, type the below command
				* vue create name_of_project (optional in this repository, already created)
		
	At VueDjangoEcommerce project:
		Access project directory using terminal, go to vue_ecommerce, run below command in frontend project directory
			* cd vue_ecommerce
		
		Dependency must run to smooth the project:
			* npm install axios (for connection between services)
			* npm install bulma (for frontend dependency)
			
		To start vue:
			** npm run serve
		
		
			
		
			