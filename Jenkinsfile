node
{
  parallel firstBranch: {
      stage('git')
      {
        git 'https://github.com/pvarjun3/dynamicweb.git'
      }
    }, secondBranch: {
      stage('mailer')
      {
        mail bcc: '', body: 'sdfjsdfjsd', cc: '', from: '', replyTo: '', subject: 'hi', to: 'malli.tech1993@gmail.com'
      }
    },
      failFast : true
  }

       
