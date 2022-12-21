# Pie_Chart
plt.figure(figsize=(10, 8))
y = np.array([400, 400, 1268])
mylabels = ["TSKB", "ISGYO", "SKNBNK"]
myexplode =[0.1,0,0]
colors_list = [ 'blue', 'green', 'gold']
plt.pie(y, labels=mylabels, labeldistance=0.7,shadow=True, pctdistance=1.1,  autopct="%.2f", explode=myexplode, colors=colors_list)
plt.legend()
plt.show()
