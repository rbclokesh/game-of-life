
node {
	stage('git'){
		//git code
			git 'https://github.com/rbclokesh/game-of-life.git'
				} 
					stage('build'){
						//build code
							sh label: '', script: 'mvn clean package'
								}
									stage('archiv'){
										// This step should not normally be used in your script. 	Consult the inline help for details.
											archive 'gameoflife-web/target/*.war'
												}
													stage('junit test reports'){
														//publish junit test reports
															junit 'gameoflife-web/*.xml'
																}

																}
