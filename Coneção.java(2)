import java.sql.Connection;
import java.sql.DriverManager;

public class Conexao {

    public static Connection conectar() {
        try {
            return DriverManager.getConnection(
                "jdbc:mysql://localhost:3306/restaurantedosdeves1",
                "root",
                "989227059",
            );
        } catch (Exception e) {
            throw new RuntimeException("Erro na conexão: " + e);
        }
    }
}
