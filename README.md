# patient-system
patient system records number of patients and their finacial data
The ribo is creatting by Maria 
num_student=int(input('how many student?'))
subj_type=int(input('enter your subj_type:(2cr.hrs=2) or (3cr.hrs=3):'))
percentage_of_stu =0
percentage_of_all_f=0
percentage_of_all_p=0
percentage_of_all_g=0
percentage_of_all_v=0
percentage_of_all_e=0
result=0
fail=0
pas=0
good=0
very_good=0
excelent=0
while  num_student>0:
    if subj_type ==2:
        mid_term = int(input('enter your mid_term :'))
        final = int(input('enter your final mark :'))
        result = mid_term + final

        if result>=0 and result<=39:
            fail+=1
            percentage_of_stu=rsult/100 *100
            percentage_of_all_f=fail/num_student*100
            print('U R fail and your percentage is{}'.format(percentage_of_stu))
        if result>=40 and result<= 59:
            pas+=1
            percentage_of_stu = result /100 *100
            percentage_of_all_p=pas / num_student * 100
            print('U R pass and your percentage is{}'.format(percentage_of_stu))
        if result >= 60 and result <= 79:
            good+=1
            percentage_of_stu = result / 100 *100
            percentage_of_all_g= good / num_student * 100
            print('U R good and your percentage is{}'.format(percentage_of_stu))
        if result >= 80 and result <= 89:
            very_good+=1
            percentage_of_stu = result /100 *100
            percentage_of_all_v=  very_good / num_student * 100
            print('U R  very good and your percentage is{}'.format(percentage_of_stu))
        if result >= 90 and result <= 100:
            excelent+=1
            percentage_of_stu = result /100 *100
            percentage_of_all_e=excelent / num_student * 100
            print('U R  Excellent and your percentage is{}'.format(percentage_of_stu))
        num_student-=1
    print('total number of student there are fail={},total number of student pass{},total number of student are good={}/'
          ' ,total number of student are very good ={},total number of student are excelent={}'.format(fail, pas, good, very_good, excelent))
    print('the percentage of student are fail{},the percentage of student are pass{}, the percentage of student are good{}/'
          'the percentage of student are very good{},the percentage of student are excellent{}/'
          ''.format(percentage_of_all_f,percentage_of_all_p,percentage_of_all_g,percentage_of_all_v,percentage_of_all_e))
    if subj_type==3:
        practical = int(input('enter your practical: '))
        mid_term = int(input('enter your mid_term :'))
        final = int(input('enter your final mark :'))
        result = mid_term + final
        if result==70:
            fail+=1
            percentage_of_stu=rsult/150 *100
            percentage_of_all=fail / num_student * 100
            print('U R fail and your percentage is{}'.format(percentage_of_stu))
        if result>=75 and result<= 96:
            pas+=1
            percentage_of_stu = result /150 *100
            percentage_of_all=pas/ num_student * 100
            print('U R pass and your percentage is{}'.format(percentage_of_stu))
        if result >= 97and result <= 119:
            good+=1
            percentage_of_stu = result / 150 *100
            percentage_of_all_f =good/ num_student * 100
            print('U R good and your percentage is{}'.format(percentage_of_stu))
        if result >= 120 and result <= 143:
            very_good+=1
            percentage_of_stu = result /150 *100
            percentage_of_all=very_good/ num_student * 100
            print('U R  very good and your percentage is{}'.format(percentage_of_stu))
        if result >= 135 and result <= 150:
            excelent+=1
            percentage_of_stu = result /150 *100
            percentage_of_all =excelent/ num_student * 100
            print('U R  Excellent and your percentage is{}'.format(percentage_of_stu))
    print('total number of student are fail={},  total number of student there are pass{},total number of student/'
          ' there are good={} ,total number of student there are very good ={},total number of student/'
              '/there are excelent={}'.format(fail,pas,good, very_good,excelent))
    print('the percentage of student are fail{},the percentage of student are pass{}, the percentage of student are good{}/'
          'the percentage of student are very good{},the percentage of student are excellent{}/'
          ''.format(percentage_of_all_f,percentage_of_all_p,percentage_of_all_g,percentage_of_all_v,percentage_of_all_e))
print()

#end
