### Hi there 👋

import Foundation
import UIKit
import CryptoKit
import CoreML

// MARK: - Caique Cayres GitHub Profile
class CaiqueCayresProfile: UIViewController {

    // MARK: - Properties
    let name = "Caique Cayres"
    let role = "iOS Developer & Tech Enthusiast"
    let interests = ["iOS Development", "AI", "Cryptocurrency"]

    // MARK: - Initialization
    override func viewDidLoad() {
        super.viewDidLoad()
        print("👋 Olá, bem-vindo ao meu perfil do GitHub!")
        displaySkills()
        displayProjects()
        connectWithMe()
    }

    // MARK: - Methods
    func displaySkills() {
        let skills = [
            "iOS Development": "Experiência em criar aplicativos iOS funcionais e intuitivos.",
            "AI Enthusiasm": "Explorando as possibilidades da inteligência artificial.",
            "Crypto Passion": "Apaixonado pelo impacto transformador das criptomoedas."
        ]
        print("💼 Habilidades: \(skills)")
    }

    func displayProjects() {
        let projects = [
            "App iOS [Nome do Projeto]": "Descrição breve do projeto.",
            "Projeto de IA [Nome do Projeto]": "Descrição breve do projeto IA.",
            "Análise de Cripto [Nome do Projeto]": "Descrição breve do projeto de criptomoeda."
        ]
        print("🌟 Projetos em Destaque: \(projects)")
    }

    func connectWithMe() {
        let socialLinks = [
            "LinkedIn": "[LinkedIn URL]",
            "Twitter": "[Twitter URL]",
            "Email": "seuemail@example.com"
        ]
        print("🔗 Vamos nos conectar: \(socialLinks)")
    }

}

// MARK: - Executar perfil
let meuPerfil = CaiqueCayresProfile()
meuPerfil.viewDidLoad()


<!--
**CaiqueCayres/CaiqueCayres** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
