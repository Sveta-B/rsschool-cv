# rsschool-cv

**Sveta Brass**

### Contact details:
 **Email:** 9624996@gmail.com
 **Discord:** Svetlana#8702


### Skills:
* Git
* Swift
* OOP
* Firebase
* Realm

### Code examples: 
 
    @IBAction func pressedLogIn(_ sender: UIButton) {
    APIManager.singIn(email: emailTextField.text,   password: passwordTextField.text) { (result) in
    switch result {
    case .success:
    let storyboard = UIStoryboard(name: "Main", bundle: nil)
    let vc = storyboard.instantiateViewController(identifier: "MainTabBarViewController") as! MainTabBarViewController
    vc.modalPresentationStyle = .fullScreen
    self.present(vc, animated: true, completion: nil)
    case .failure(let error):
    print(error)
    self.showAlert(mesage: "Wrong password or email", title: "Error")
    }
    }
    }

### Summary:
My goal is to become a developer at a major emerging company

### Education:
Belarusian State Academy of Communications

### Language:
* English A2
   

