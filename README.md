# DEVELOP
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace acervo.DAL
{
    class DataContextFactory
    {
        private static acervoDataContext dataContext;
        acervoDataContext DataContext

        {  

            get
            {
                if (dataContext == null)
                    dataContext = new acervoDataContext();
                return dataContext;

            }
        }
    }
}

    

