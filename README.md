Marcos Gonzalez
800651799

Training for both programs was performed using cpu:

Program 1:
transform.Resize function was kept to the provided 227,227 
Program 2:
transform.Resize function was changed to 224,224. 
self.fc1 = nn.Linear(in_features=(256*X*Y),out_features=4096), was calculated using resize of 224, X = 2, Y = 2
