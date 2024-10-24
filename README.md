# -Project1-Team20
项目1：轨道交通调度管理系统_20组
class Train:
        def __init__(self,train_number,departure_time,arrival_time,status):
            self.train_number = train_number
            self.departure_.time = train_number
            self.arrival_time = arrival_time
            self.status = status
def     generate_report(train):
        report = f"Train Number:{train.train_number}\n"
        report += f"Departure Time:{train.departure_time}\n"
        report += f"Arrival Time:{train.arrival_time}\n"
        report += f"Status:{train.status}\n"
        return report
#示例用法
train = Train("T123","08:00","12:00","On time")
print(generate_report(train))
