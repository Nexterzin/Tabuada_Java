import javax.swing.JFrame;
import javax.swing.JLabel;
import javax.swing.JPanel;
import javax.swing.ImageIcon;
import javax.swing.JButton;
import javax.swing.JOptionPane;
import java.awt.BorderLayout;
import java.awt.GridBagLayout;
import java.awt.GridBagConstraints;
import java.awt.event.ActionEvent;
import java.awt.event.ActionListener;

public class Tabuada {

    public static void main(String[] args) {
        int largura = 300;
        int altura = 400;

        JFrame frame = new JFrame("Tabuada");
        frame.setSize(largura, altura);
        frame.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);

        JPanel panel = new JPanel(new GridBagLayout());
        
        GridBagConstraints constraints = new GridBagConstraints();
        constraints.gridx = 0;
        constraints.gridy = 0;
        constraints.gridwidth = 2;
        constraints.anchor = GridBagConstraints.CENTER;

        JButton button = new JButton("ABRIR PARA A TABUADA");
        panel.add(button, constraints);

        JLabel imageLabel = new JLabel();
        constraints.gridy = 1;
        panel.add(imageLabel, constraints);

        // Ação quando o botão é clicado
        button.addActionListener(new ActionListener() {
            @Override
            public void actionPerformed(ActionEvent e) {
                String input = JOptionPane.showInputDialog(frame, "Digite um número: ");
                int numero = Integer.parseInt(input);

                ImageIcon imagem = null;

                if (numero == 1) {
                    imagem = new ImageIcon("srr/tabuada1.png");
                } else if (numero == 2) {
                    imagem = new ImageIcon("srr/tabuada2.png");
                }else if (numero == 3) {
                    imagem = new ImageIcon("srr/tabuada3.png");
                }else if (numero == 4) {
                    imagem = new ImageIcon("srr/tabuada4.png");
                }else if (numero == 5) {
                    imagem = new ImageIcon("srr/tabuada5.png");
                }else if (numero == 6) {
                    imagem = new ImageIcon("srr/tabuada6.png");
                }else if (numero == 7) {
                    imagem = new ImageIcon("srr/tabuada7.png");
                }else if (numero == 8) {
                    imagem = new ImageIcon("srr/tabuada8.png");
                }else if (numero == 9) {
                    imagem = new ImageIcon("srr/tabuada9.png");
                }else if (numero == 10) {
                    imagem = new ImageIcon("srr/tabuada10.png");
                }

                if (imagem != null) {
                    imageLabel.setIcon(imagem);
                } else {
                    imageLabel.setIcon(null);
                }
            }
        });

        frame.add(panel);
        frame.setVisible(true);
    }
}
