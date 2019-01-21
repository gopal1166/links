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

# upgrade pip:
        $ sudo -H  python -m  pip install --upgrade pip
        
        
# React js Loops and callbacks
        http://www.codeblocq.com/2015/12/Loops-and-callbacks-in-React/

# swith user to root:
        $ sudo su -
        
        
# Django:
# sending email error: SMTPAuthenticationError(code, resp)
 sol: https://accounts.google.com/DisplayUnlockCaptcha
  
 
# To view the error.log in apache2:
        path /var/log/apache2
        $ less error.log
        then Shift+G

# Error getting while try to run celery worker process
        ImportError: No module named celery
        Sol: may be celery pkg is not installed 
                        or
             we not pointing the correct virual environment
             
             
# react grid virtual scroling:
       https://devexpress.github.io/devextreme-reactive/react/grid/docs/guides/virtual-scrolling/
       
# React js dashboard
        http://akveo.com/blur-admin/#/tables/smart
        
# React js:
   To go back to the previous page
   https://stackoverflow.com/questions/30915173/react-router-go-back-a-page-how-do-you-configure-history
   
   import withRouter

import { withRouter } from 'react-router-dom';
Export your component as:

export withRouter(nameofcomponent) 
Example, on button click, call goBack:

<button onClick={this.props.history.goBack()}>Back</button>


# React js:
   Modals:
   https://reactstrap.github.io/components/modals/


