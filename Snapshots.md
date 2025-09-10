# Snapshots

Snapshots são cópias incrementais e pontuais dos dados de armazenamento (EBS) anexados a instâncias EC2. Eles capturam o estado de "arquivo" em um momento específico,
servindo como base para backup, recuperação de desastres e replicação de ambientes.

## Como funcionam?
- Backups Incrementais: Após o primeiro snapshot completo, os próximos salvam apenas os blocos de dados que foram alterados desde o último snapshot. Isso otimiza custo e tempo de armazenamento.
- Armazenamento: São armazenados automaticamente no Amazon S3, garantindo alta durabilidade e disponibilidade.

## Principais Vantagens:
- Backup automatizado: Podem ser agendados para criar políticas de backup regulares e consistentes.
- Recuperação de desastres: Permitem restaurar um volume inteiro para um estado anterior em caso de falhas ou corrupção de dados.
- Replicação de ambientes: Facilitam a criação de novos volumes idênticos em outras zonas de disponibilidade ou regiões AWS.

# Snapshots
Snapshots are incremental, point-in-time copies of the storage data (EBS) attached to EC2 instances. They capture the state of a "file" at a specific moment, 
serving as the foundation for backup, disaster recovery, and environment replication.

## How do they work?
- Incremental Backups: After the first full snapshot, subsequent ones only save the data blocks that have changed since the last snapshot. This optimizes storage costs and time.
- Storage: They are automatically stored in Amazon S3, ensuring high durability and availability.

## Key Advantages:
- Automated Backup: Can be scheduled to create regular and consistent backup policies.
- Disaster Recovery: Allow you to restore an entire volume to a previous state in case of failures or data corruption.
- Environment Replication: Facilitate the creation of new identical volumes in other Availability Zones or AWS regions.
