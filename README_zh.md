# 宝可梦数据分析

本项目提供了使用SQL和Python分析宝可梦数据的工具和脚本。它包括一个数据库架构、辅助脚本和分析查询，用于获取有关宝可梦特征、遭遇和可能进化的见解。

## 文件
- **`PokemonDataAnalysis.dump.sql`**：PostgreSQL数据库转储文件，用于设置数据库架构。
- **`attack_damage`**：存储与宝可梦攻击计算相关的结果。
- **`encounter_summary`**：总结宝可梦遭遇数据。
- **`helpers.py`**：用于清理和格式化数据输入的Python辅助函数。
- **`helpers.sql`**：包含数据库操作实用函数的SQL脚本。
- **`my_pokemon`**：包含个性化宝可梦数据。
- **`pokemon_density`**：分析各个区域的宝可梦密度。
- **`possible_evolutions`**：记录宝可梦的潜在进化路径。

## 功能
1. **数据库设置**：使用给定的架构初始化PostgreSQL数据库。
2. **宝可梦分析**：
   - 分析宝可梦攻击统计信息。
   - 总结宝可梦遭遇。
   - 探索进化可能性和区域密度。
3. **辅助函数**：用于增强功能的Python和SQL工具。

## 技术栈
- **数据库**：PostgreSQL
- **编程语言**：SQL、Python

## 使用方法
1. 导入数据库架构：
   ```bash
   psql -U <用户名> -d <数据库名称> -f PokemonDataAnalysis.dump.sql
   ```

2. 根据需要使用Python辅助函数：
   ```bash
   python helpers.py
   ```

3. 运行SQL脚本进行数据分析：
   ```bash
   psql -U <用户名> -d <数据库名称> -f helpers.sql
   ```

## 作者
本项目是COMP3311课程的一部分，旨在用于教育目的，但也可以适应更广泛的数据分析需求。
