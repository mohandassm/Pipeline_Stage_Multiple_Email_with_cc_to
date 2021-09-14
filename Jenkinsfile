node {
stage('Email-Notification')
		{
		mail 
		bcc: '', 
        body:" Hi All,\n 
		Please find the below details for Docker server deployment.\n 
		Jenkins Build Number = ${env.BUILD_NUMBER}\n  
		Please go to this URL for Git Change logs = ${env.BUILD_URL}\n 
		Please go to this URL for more details = ${env.BUILD_URL}consoleText",
        cc: 'Email-1,Email-2,Email-3,...', 
		from: '', 
		replyTo: '',
		subject: "${env.BUILD_NUMBER}", 
		to: 'Email-1,Email-2,Email-3,....'
		}
}
