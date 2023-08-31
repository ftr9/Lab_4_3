## Question

![image](https://github.com/ftr9/Lab_4_3/assets/60734475/e20728c5-705f-4d9d-830d-fa7bcb8df2f1)

## Step - 1 Inside the Program.cs file

```
namespace Lab_4_3
{
    internal static class Program
    {
        [STAThread]
        static void Main()
        {
            // To customize application configuration such as set high DPI settings or default font,
            // see https://aka.ms/applicationconfiguration.
            ApplicationConfiguration.Initialize();
            Application.Run(new Form1());
        }
    }
}
```

## Step - 2 Inside the Form1.Designer.cs file

```
namespace Lab_4_3
{
    partial class Form1
    {
        /// <summary>
        ///  Required designer variable.
        /// </summary>
        private System.ComponentModel.IContainer components = null;

        /// <summary>
        ///  Clean up any resources being used.
        /// </summary>
        /// <param name="disposing">true if managed resources should be disposed; otherwise, false.</param>
        protected override void Dispose(bool disposing)
        {
            if (disposing && (components != null))
            {
                components.Dispose();
            }
            base.Dispose(disposing);
        }

        #region Windows Form Designer generated code

        /// <summary>
        ///  Required method for Designer support - do not modify
        ///  the contents of this method with the code editor.
        /// </summary>
        private void InitializeComponent()
        {
            button1 = new Button();
            button2 = new Button();
            button3 = new Button();
            button4 = new Button();
            flowLayoutPanel1 = new FlowLayoutPanel();
            panel1 = new Panel();
            Ecommerce = new Label();
            flowLayoutPanel1.SuspendLayout();
            panel1.SuspendLayout();
            SuspendLayout();
            //
            // button1
            //
            button1.Location = new Point(3, 59);
            button1.Name = "button1";
            button1.Size = new Size(150, 50);
            button1.TabIndex = 1;
            button1.Text = "Orders";
            button1.UseVisualStyleBackColor = true;
            //
            // button2
            //
            button2.Location = new Point(3, 3);
            button2.Name = "button2";
            button2.Size = new Size(150, 50);
            button2.TabIndex = 2;
            button2.Text = "Delivery";
            button2.UseVisualStyleBackColor = true;
            //
            // button3
            //
            button3.Location = new Point(3, 115);
            button3.Name = "button3";
            button3.Size = new Size(150, 50);
            button3.TabIndex = 3;
            button3.Text = "Users List";
            button3.UseVisualStyleBackColor = true;
            //
            // button4
            //
            button4.Location = new Point(3, 171);
            button4.Name = "button4";
            button4.Size = new Size(150, 50);
            button4.TabIndex = 4;
            button4.Text = "Exit";
            button4.UseVisualStyleBackColor = true;
            //
            // flowLayoutPanel1
            //
            flowLayoutPanel1.BackColor = SystemColors.ActiveCaption;
            flowLayoutPanel1.Controls.Add(button2);
            flowLayoutPanel1.Controls.Add(button1);
            flowLayoutPanel1.Controls.Add(button3);
            flowLayoutPanel1.Controls.Add(button4);
            flowLayoutPanel1.Location = new Point(-1, 71);
            flowLayoutPanel1.Name = "flowLayoutPanel1";
            flowLayoutPanel1.Size = new Size(156, 376);
            flowLayoutPanel1.TabIndex = 6;
            //
            // panel1
            //
            panel1.BackColor = SystemColors.ActiveCaption;
            panel1.Controls.Add(Ecommerce);
            panel1.ForeColor = SystemColors.ActiveCaptionText;
            panel1.Location = new Point(-1, 0);
            panel1.Name = "panel1";
            panel1.Size = new Size(802, 68);
            panel1.TabIndex = 7;
            //
            // Ecommerce
            //
            Ecommerce.AutoSize = true;
            Ecommerce.Font = new Font("Segoe UI", 15F, FontStyle.Regular, GraphicsUnit.Point);
            Ecommerce.Location = new Point(32, 20);
            Ecommerce.Name = "Ecommerce";
            Ecommerce.Size = new Size(146, 35);
            Ecommerce.TabIndex = 0;
            Ecommerce.Text = "Ecommerce";
            Ecommerce.Click += label1_Click;
            //
            // Form1
            //
            AutoScaleDimensions = new SizeF(8F, 20F);
            AutoScaleMode = AutoScaleMode.Font;
            ClientSize = new Size(800, 450);
            Controls.Add(panel1);
            Controls.Add(flowLayoutPanel1);
            Name = "Form1";
            Text = "Form1";
            flowLayoutPanel1.ResumeLayout(false);
            panel1.ResumeLayout(false);
            panel1.PerformLayout();
            ResumeLayout(false);
        }

        #endregion

        private Button button1;
        private Button button2;
        private Button button3;
        private Button button4;
        private FlowLayoutPanel flowLayoutPanel1;
        private Panel panel1;
        private Label Ecommerce;
    }
}
```

## Step - 3 - Output

![image](https://github.com/ftr9/Lab_4_3/assets/60734475/82fd7a82-5d9b-4df6-85ed-0d81432d45c2)
