# AC7Python
C:\Users\MeGaTrON\Desktop\faculdadE\lms>python manage.py test --failfast --verbosity 2
Traceback (most recent call last):
  File "manage.py", line 15, in <module>
    execute_from_command_line(sys.argv)
  File "C:\Users\MeGaTrON\AppData\Local\Programs\Python\Python37-32\lib\site-packages\django\core\management\__init__.py", line 381, in execute_from_command_line
    utility.execute()
  File "C:\Users\MeGaTrON\AppData\Local\Programs\Python\Python37-32\lib\site-packages\django\core\management\__init__.py", line 357, in execute
    django.setup()
  File "C:\Users\MeGaTrON\AppData\Local\Programs\Python\Python37-32\lib\site-packages\django\__init__.py", line 24, in setup
    apps.populate(settings.INSTALLED_APPS)
  File "C:\Users\MeGaTrON\AppData\Local\Programs\Python\Python37-32\lib\site-packages\django\apps\registry.py", line 112, in populate
    app_config.import_models()
  File "C:\Users\MeGaTrON\AppData\Local\Programs\Python\Python37-32\lib\site-packages\django\apps\config.py", line 198, in import_models
    self.models_module = import_module(models_module_name)
  File "C:\Users\MeGaTrON\AppData\Local\Programs\Python\Python37-32\lib\importlib\__init__.py", line 127, in import_module
    return _bootstrap._gcd_import(name[level:], package, level)
  File "<frozen importlib._bootstrap>", line 1006, in _gcd_import
  File "<frozen importlib._bootstrap>", line 983, in _find_and_load
  File "<frozen importlib._bootstrap>", line 967, in _find_and_load_unlocked
  File "<frozen importlib._bootstrap>", line 677, in _load_unlocked
  File "<frozen importlib._bootstrap_external>", line 724, in exec_module
  File "<frozen importlib._bootstrap_external>", line 860, in get_code
  File "<frozen importlib._bootstrap_external>", line 791, in source_to_code
  File "<frozen importlib._bootstrap>", line 219, in _call_with_frames_removed
  File "C:\Users\MeGaTrON\Desktop\faculdadE\lms\lms_app\models.py", line 3
    class Disciplina(models.Model):
    ^
IndentationError: unexpected indent
