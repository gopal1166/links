# links

pagination and search filter for Table in front end:

https://react-bootstrap-table.github.io/react-bootstrap-table2/storybook/index.html?selectedKind=Pagination&selectedStory=Basic%20Pagination%20Table&full=0&addons=1&stories=1&panelRight=0&addonPanel=storybook%2Factions%2Factions-panel

props:
https://react-bootstrap-table.github.io/react-bootstrap-table2/docs/table-props.html


# django:
Topic: Creating custom user model and custom authentication in Django &
        adding custom user model to the django admin panel.
        Because by default custom user model is not registered with admin panel
      
https://www.pythoncircle.com/post/28/creating-custom-user-model-and-custom-authentication-in-django/


# Adding Authorization: Token 'token string' header to the requests using interceptors

https://gist.github.com/srph/38f67a10e991b6cb2d83



# Django:
# storing python object(instance) in django  request.session
ex: connection obje
       request.session['connection'] = connection

Error:TypeError: <Connection host=dllgststapp2v.jdadelivers.com port=2022> is not JSON serializable

sol:
SESSION_SERIALIZER = 'django.contrib.sessions.serializers.PickleSerializer'
SESSION_EXPIRE_AT_BROWSER_CLOSE=True
