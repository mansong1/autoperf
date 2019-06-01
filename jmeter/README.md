============Build, tag and push the base image============

		docker build --tag="mansong/jmbase:latest"
		docker push mansong/jmbase:latest

============Build, tag and push the master image============

		docker build --tag="mansong/jmmaster:latest"
		docker push mansong/jmmaster:latest

============Build, tag and push the slave image============

		docker build --tag="mansong/jmslave:latest"
		docker push mansong/jmslave:latest