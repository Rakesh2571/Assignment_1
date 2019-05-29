using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;
using ConsoleApp14;
using NUnit.Framework;

namespace SENG8040_Assignment_Test
{

    [TestFixture]
    class SENG8040_Assignment1_Unittest
    {
        [Test]
        public void Getlenght_Input3_expectedLenghtEquals3()
        {
            //Arrange
            int l = 3;
            int w = 4;
                Rectangle recobj = new Rectangle(l, w);

            //Act
            int length = recobj.GetLength();
            //Assert
            Assert.AreEqual(l, length);
        }

        [Test]
        public void Getlenght_Input5_expectedLenghtEquals5()
        {
            //Arrange
            int l = 5;
            int w = 4;
                Rectangle recobj = new Rectangle(l, w);

            //Act
            int length = recobj.GetLength();
            //Assert
            Assert.AreEqual(l, length);
        }
        [Test]
        public void Getlenght_Input6_expectedLenghtEquals6()
        {
            //Arrange
            int l = 6;
            int w = 4;
                 Rectangle recobj = new Rectangle(l, w);

            //Act
            int length = recobj.GetLength();
            //Assert
            Assert.AreEqual(l, length);
        }
        [Test]
        public void SetLength_Input8_expectedLenghtEquals8()
        {
            //Arrange
            int l = 8;
            int w = 4;
                  Rectangle recobj = new Rectangle(l, w);

            //Act
            int length = recobj.SetLength(l);
            //Assert
            Assert.AreEqual(l, length);
        }
        [Test]
        public void SetLength_Input9_expectedLenghtEquals9()
        {
            //Arrange
            int l = 9;
            int w = 4;
                  Rectangle recobj = new Rectangle(l, w);

            //Act
            int length = recobj.SetLength(l);
            //Assert
            Assert.AreEqual(l, length);
        }
        [Test]
        public void SetLength_Input11_expectedLenghtEquals11()
        {
            //Arrange
            int l = 11;
            int w = 4;
                  Rectangle recobj = new Rectangle(l, w);

            //Act
            int length = recobj.SetLength(l);
            //Assert
            Assert.AreEqual(l, length);
        }
        [Test]
        public void GetWidth_Input4_expectedWidthEquals4()
        {
            //Arrange
            int l = 11;
            int w = 4;
            Rectangle recobj = new Rectangle(l, w);

            //Act
            int width = recobj.GetWidth();
            //Assert
            Assert.AreEqual(w, width);
        }
        [Test]
        public void GetWidth_Input5_expectedWidthEquals5()
        {
            //Arrange
            int l = 11;
            int w = 5;
            Rectangle recobj = new Rectangle(l, w);

            //Act
            int width = recobj.GetWidth();
            //Assert
            Assert.AreEqual(w, width);
        }
        [Test]
        public void GetWidth_Input6_expectedWidthEquals6()
        {
            //Arrange
            int l = 11;
            int w = 6;
            Rectangle recobj = new Rectangle(l, w);

            //Act
            int width = recobj.GetWidth();
            //Assert
            Assert.AreEqual(w, width);
        }
        [Test]
        public void SetWidth_Input7_expectedWidthEquals7()
        {
            //Arrange
            int l = 11;
            int w = 7;
            Rectangle recobj = new Rectangle(l, w);

            //Act
            int width = recobj.SetWidth(w);
            //Assert
            Assert.AreEqual(w, width);
        }
        [Test]
        public void SetWidth_Input8_expectedWidthEquals8()
        {
            //Arrange
            int l = 11;
            int w = 8;
            Rectangle recobj = new Rectangle(l, w);

            //Act
            int width = recobj.SetWidth(w);
            //Assert
            Assert.AreEqual(w, width);
        }
        [Test]
        public void SetWidth_Input9_expectedWidthEquals9()
        {
            //Arrange
            int l = 11;
            int w = 8;
            Rectangle recobj = new Rectangle(l, w);

            //Act
            int width = recobj.SetWidth(w);
            //Assert
            Assert.AreEqual(w, width);
        }
        [Test]
        public void GetPerimeter_Input2and2_expectedPerimeterEquals8()
        {
            //Arrange
            int l = 2;
            int w = 2;
            int expPerimeter = (l * 2) + (w * 2);

            Rectangle recobj = new Rectangle(l, w);

            //Act
            int actPerimeter = recobj.GetPerimeter();
            //Assert
            Assert.AreEqual(expPerimeter, actPerimeter);
        }
        [Test]
        public void GetPerimeter_Input3and3_expectedPerimeterEquals12()
        {
            //Arrange
            int l = 3;
            int w = 3;
            int expPerimeter = (l * 2) + (w * 2);

            Rectangle recobj = new Rectangle(l, w);

            //Act
            int actPerimeter = recobj.GetPerimeter();
            //Assert
            Assert.AreEqual(expPerimeter, actPerimeter);
        }
        [Test]
        public void GetPerimeter_Input4and4_expectedPerimeterEquals16()
        {
            //Arrange
            int l = 4;
            int w = 4;
            int expPerimeter = (l * 2) + (w * 2);

            Rectangle recobj = new Rectangle(l, w);

            //Act
            int actPerimeter = recobj.GetPerimeter();
            //Assert
            Assert.AreEqual(expPerimeter, actPerimeter);
        }
        [Test]
        public void GetArea_Input2and3_expectedAreaEquals6()
        {
            //Arrange
            int l = 2;
            int w = 3;
            int expArea = (l * w);

            Rectangle recobj = new Rectangle(l, w);

            //Act
            int actArea = recobj.GetArea();
            //Assert
            Assert.AreEqual(expArea, actArea);
        }
        [Test]
        public void GetArea_Input3and4_expectedAreaEquals12()
        {
            //Arrange
            int l = 3;
            int w = 4;
            int expArea = (l * w);

            Rectangle recobj = new Rectangle(l, w);

            //Act
            int actArea = recobj.GetArea();
            //Assert
            Assert.AreEqual(expArea, actArea);
        }
        [Test]
        public void GetArea_Input4and4_expectedAreaEquals16()
        {
            //Arrange
            int l = 4;
            int w = 4;
            int expArea = (l * w);

            Rectangle recobj = new Rectangle(l, w);

            //Act
            int actArea = recobj.GetArea();
            //Assert
            Assert.AreEqual(expArea, actArea);
        }
    }
}
