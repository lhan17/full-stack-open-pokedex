# Exercise 11.1

## Example of Continous Integration steps of Python Application

The choice of framework/tool/setup in parenthesis.

1. Lint: For linting we can use Pylint and PyFlakes. These check the code for errors, unintended results, and dangerous code patterns. (Pylint)
2. Build: For build, Python application can use setuptools, Pyinstaller or PyOxidizer. These build tools keep all the necessary code and dependencies in an installable and executable package. (PyInstaller)
3. Test: For test we can use PyTest, Robot or Nose2. Testing keeps us from putting broken features to the code or keeps us from breaking existing features. (PyTest)
4. Package: For packaging we can use pip or conda. These are the most popular ones. (pip)
5. Deploy: For deployment, python applications can use Docker, Heroku, google cloud or AWS. These tools help developers to deploy the application to cloud server or a container, making it accessible to the world.

### Continuous Integration set up alternatives

There are many CI set ups for instance Travis CI, Circle CI, Bamboo and Azure DevOps. (DevOps)

### Self-hosted or a cloud-based environment?

Because six people are working on a project, I would just go with a cloud-based environment Azure DevOps. Reasons for this is that firstly Azure DevOps provides strong support for python application. Secondly, it has integrated source control which helps you manage Python codebase and collaborate with your team. Ultimately Azure provides large ecosystem of extensions.
