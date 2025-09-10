# EBS (Armazenamento de Blocos Elástico)

O **EBS** é fundamental para cargas de trabalho em que a instância necessita de armazenamento acoplado e exclusivo, permitindo leitura e escrita de dados.
Ou seja, caso a instância seja desligada de alguma maneira, os dados obtidos por meio do EBS continuarão existindo de forma independente, **garantindo segurança da informação**.
Além disso, ele possibilita a troca da instância EC2 sem perda de dados. Assim, percebe-se que seu uso é muito importante, pois gera redundância dos dados.

O tipo de volume pode ser **SSD** ou **HD**, dependendo do ecossistema da aplicação e do entendimento do uso.

# EBS (Elastic Block Store)

**EBS** is fundamental for workloads where an instance requires attached and dedicated storage, allowing data to be read and written.
This means that if the instance is shut down for any reason, the data stored on the EBS will persist independently, **ensuring data security**.
Additionally, it allows the EC2 instance to be replaced without data loss. Therefore, its use is very important, as it provides a certain level of data redundancy.

The volume type can be **SSD** or **HDD**, depending on the application ecosystem and intended usage.
