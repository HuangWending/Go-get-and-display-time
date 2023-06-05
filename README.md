# Go-get-and-display-time
Go语言获取并显示当前时间的程序
package main: 定义了一个名为"main"的包，它是一个可执行的程序入口点。
import "fmt": 导入了Go语言的fmt包，用于格式化和打印输出。
import "time": 导入了Go语言的time包，用于处理时间和日期。
func main() { ... }: 定义了程序的主函数，程序从这里开始执行。
currentTime := time.Now(): 使用time.Now()函数获取当前的时间，并将结果保存在名为currentTime的变量中。
fmt.Println("Current time:", currentTime): 使用fmt.Println()函数将字符串"Current time:"和currentTime的值打印到标准输出。这行代码将输出当前时间的文本表示形式。
