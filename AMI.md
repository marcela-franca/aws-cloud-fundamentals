# AMI (Imagens de Máquina da Amazon)

Uma AMI é um **recurso fundamental** do EC2 que funciona como um template para inicializar uma instância. Ela contém toda a configuração necessária: sistema operacional, software e permissões de acesso, ou seja, podemos fazer uma 
alusão a um template pronto. Em vez de instalar e configurar um sistema operacional do zero toda vez que você precisar de um novo servidor, você simplesmente seleciona uma AMI que já possui tudo o que você precisa pré-configurado.

## Fontes das AMIs:
*   **AWS:** Imagens oficiais, seguras e otimizadas (ex: Amazon Linux, Ubuntu, Windows Server).
*   **Próprias (Customizadas):** Você pode criar sua própria AMI a partir de uma instância EC2 configurada, permitindo padronizar e replicar ambientes específicos.

## Principal Vantagem:
As AMIs são a base para a **escalabilidade rápida e consistente**. Elas permitem que você inicialize e termine dezenas de instâncias idênticas em segundos, garantindo que todas tenham exatamente a mesma configuração.

# AMI (Amazon Machine Image)
An AMI is a fundamental EC2 resource that acts as a template for launching an instance. It contains all the necessary configuration: the operating system, software, and access permissions—in other words, we can think of it as a ready-made template. Instead of installing and configuring an operating system from scratch every time you need a new server, you simply select an AMI that already has everything you need pre-configured.

## AMI Sources:
- AWS: Official, secure, and optimized images (e.g., Amazon Linux, Ubuntu, Windows Server).
- Custom (Your Own): You can create your own AMI from a configured EC2 instance, allowing you to standardize and replicate specific environments.

## Key Advantage:
- AMIs are the foundation for rapid and consistent scalability. They allow you to launch and terminate dozens of identical instances in seconds, ensuring that all of them have the exact same configuration.
