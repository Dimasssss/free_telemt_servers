# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### **Принимаю донаты криптой для добавления и продления серверов:**
- TON (Можно отправлять TON и USDT в сети TON):
```
UQAyIvWts4-gC0b5ouoy_JNDfBEe337c7oOBqpGXFB8fJUzB
```
### **Спасибо:**
- Ivan Morozov - 20$

_Можете писать свой ник в коментарии к переводу_

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-60
- Краткое описание тарифа: 4 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 26 апреля
- Ссылка:
```bash
tg://proxy?server=s1.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## psb.hosting (2 сервера)
- Локация: Finland
- Тариф: FI-200
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 12$
- Ссылка:
```bash
tg://proxy?server=s2.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## koara.io
- Локация: Германия, Франкфурт-на-Майне
- Тариф: DE-2
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 639 RUB
- Оплачен до: 25 марта
- Ссылка:
```bash
tg://proxy?server=s3.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## landvps.ru
- Локация: Финляндия
- Тариф: FL-2
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 200 Mbps/s
- Цена в месяц: 800 RUB
- Оплачен до: 26 марта
- Ссылка:
```bash
tg://proxy?server=s4.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## rdp-onedash.ru (2 сервера)
- Локация: Нидерланды
- Тариф: Mini
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 844 RUB
- Ссылка:
```bash
tg://proxy?server=s5.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## hostvds.com
- Локация: Франция, Париж
- Тариф: Highload-2
- Краткое описание тарифа: 2 vCore, 8 Gb ram, 10 Gbit/s
- Цена в месяц: €12.57
- Ссылка:
```bash
tg://proxy?server=s6.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## 4vps.su (2 сервера)
- Локация: Польша, Варшава
- Тариф: PL-cx21
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 2 Gbit/s
- Цена в месяц: 770 RUB
- Оплачен до: 16 апреля
- Ссылка:
```bash
tg://proxy?server=s7.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

# Server Metrics 2026-03-22 13:40:56 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 59673.5 (16h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1866552
telemt_connections_bad_total 82124
telemt_connections_current 1901
telemt_connections_me_current 1901
telemt_handshake_timeouts_total 79192
telemt_upstream_connect_attempt_total 22400
telemt_upstream_connect_success_total 22399
telemt_upstream_connect_attempts_per_request{bucket="1"} 22399
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7751
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14583
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 52
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 909
telemt_me_reconnect_success_total 363
telemt_me_reader_eof_total 367
telemt_me_idle_close_by_peer_total 367
telemt_me_route_drop_no_conn_total 1297803
telemt_me_route_drop_channel_closed_total 600
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1586934
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_endpoint_quarantine_total 412
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 473
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 8783
telemt_desync_full_logged_total 2685
telemt_desync_suppressed_total 6098
telemt_desync_frames_bucket_total{bucket="1_2"} 2450
telemt_desync_frames_bucket_total{bucket="3_10"} 3299
telemt_desync_frames_bucket_total{bucket="gt_10"} 3034
telemt_pool_swap_total 66
telemt_pool_force_close_total 1977
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 322
telemt_me_draining_writers_reap_progress_total 20435
telemt_me_writer_removed_unexpected_total 358
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1458
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19196
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1941
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 36
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18458
telemt_me_writer_teardown_success_total{mode="normal"} 20654
telemt_me_writer_teardown_noop_total 20439
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 34777
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 36040
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 37142
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 39000
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 40313
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 40931
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 41090
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 41093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 41093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 41093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 41093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 41093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 41093
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 156.103854
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 41093
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 322
telemt_me_refill_failed_total 29
telemt_me_writer_restored_same_endpoint_total 322
telemt_me_writer_removed_unexpected_minus_restored_total 36
telemt_user_connections_total{user="hello"} 1584003
telemt_user_connections_current{user="hello"} 1901
telemt_user_octets_from_client{user="hello"} 24920878336 (23.21 GB)
telemt_user_octets_to_client{user="hello"} 463154132080 (431.35 GB)
telemt_user_unique_ips_current{user="hello"} 690
telemt_user_unique_ips_recent_window{user="hello"} 368
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 73039.6 (20h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3037971
telemt_connections_bad_total 283608
telemt_connections_current 1973
telemt_connections_me_current 1973
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 71291
telemt_upstream_connect_attempt_total 46906
telemt_upstream_connect_success_total 46345
telemt_upstream_connect_fail_total 496
telemt_upstream_connect_attempts_per_request{bucket="1"} 46841
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27857
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18354
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 134
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 496
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 3667
telemt_me_reconnect_success_total 1645
telemt_me_reader_eof_total 1516
telemt_me_idle_close_by_peer_total 1516
telemt_me_route_drop_no_conn_total 2845612
telemt_me_route_drop_channel_closed_total 28
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2390307
telemt_me_endpoint_quarantine_total 612
telemt_me_single_endpoint_outage_enter_total 35
telemt_me_single_endpoint_outage_exit_total 35
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 35
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 569
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 32
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 55
telemt_me_writers_warm_current 31
telemt_desync_total 9399
telemt_desync_full_logged_total 5251
telemt_desync_suppressed_total 4148
telemt_desync_frames_bucket_total{bucket="1_2"} 2213
telemt_desync_frames_bucket_total{bucket="3_10"} 3681
telemt_desync_frames_bucket_total{bucket="gt_10"} 3505
telemt_pool_swap_total 72
telemt_pool_force_close_total 2070
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 172
telemt_me_draining_writers_reap_progress_total 28752
telemt_me_writer_removed_unexpected_total 1473
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3153
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27073
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1824
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 246
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26682
telemt_me_writer_teardown_success_total{mode="normal"} 30226
telemt_me_writer_teardown_noop_total 28752
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 57546
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 58450
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 58693
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 58947
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 58975
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 58978
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 58978
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 58978
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 58978
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 58978
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 58978
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 58978
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 58978
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 9.743171
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 58978
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 172
telemt_me_refill_failed_total 91
telemt_me_writer_restored_same_endpoint_total 1366
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 35
telemt_me_writer_removed_unexpected_minus_restored_total 83
telemt_user_connections_total{user="hello"} 2401877
telemt_user_connections_current{user="hello"} 1973
telemt_user_octets_from_client{user="hello"} 28907333235 (26.92 GB)
telemt_user_octets_to_client{user="hello"} 549687669994 (511.94 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 1323
telemt_user_unique_ips_recent_window{user="hello"} 584
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 147900.7 (41h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13856267
telemt_connections_bad_total 1212560
telemt_connections_current 4281
telemt_connections_me_current 4281
telemt_handshake_timeouts_total 349342
telemt_upstream_connect_attempt_total 53720
telemt_upstream_connect_success_total 53638
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 53646
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24302
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29106
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 224
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2457
telemt_me_reconnect_success_total 1281
telemt_me_reader_eof_total 1224
telemt_me_idle_close_by_peer_total 1223
telemt_me_route_drop_no_conn_total 12080998
telemt_me_route_drop_channel_closed_total 119
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 11116282
telemt_me_endpoint_quarantine_total 942
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 1101
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 39
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 45
telemt_desync_total 45103
telemt_desync_full_logged_total 14328
telemt_desync_suppressed_total 30775
telemt_desync_frames_bucket_total{bucket="1_2"} 10208
telemt_desync_frames_bucket_total{bucket="3_10"} 17649
telemt_desync_frames_bucket_total{bucket="gt_10"} 17246
telemt_pool_swap_total 159
telemt_pool_force_close_total 5440
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 862
telemt_me_draining_writers_reap_progress_total 48983
telemt_me_writer_removed_unexpected_total 1180
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4259
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 45239
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 41
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5008
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 432
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 43543
telemt_me_writer_teardown_success_total{mode="normal"} 49498
telemt_me_writer_teardown_noop_total 49032
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 89221
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 92171
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 93634
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 95667
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 97133
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 97999
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 98500
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 98530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 98530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 98530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 98530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 98530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 98530
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 252.498721
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 98530
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 862
telemt_me_refill_failed_total 65
telemt_me_writer_restored_same_endpoint_total 1103
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 70
telemt_user_connections_total{user="hello"} 11104193
telemt_user_connections_current{user="hello"} 4281
telemt_user_octets_from_client{user="hello"} 159798113940 (148.82 GB)
telemt_user_octets_to_client{user="hello"} 2959148077784 (2.69 TB)
telemt_user_unique_ips_current{user="hello"} 1725
telemt_user_unique_ips_recent_window{user="hello"} 777
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 147901.0 (41h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10275161
telemt_connections_bad_total 964166
telemt_connections_current 4410
telemt_connections_me_current 4410
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 307568
telemt_upstream_connect_attempt_total 80081
telemt_upstream_connect_success_total 78941
telemt_upstream_connect_fail_total 819
telemt_upstream_connect_attempts_per_request{bucket="1"} 79760
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43440
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31666
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 157
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3678
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 819
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 182
telemt_me_reconnect_attempts_total 3692
telemt_me_reconnect_success_total 1465
telemt_me_reader_eof_total 1339
telemt_me_idle_close_by_peer_total 1339
telemt_me_route_drop_no_conn_total 4095022
telemt_me_route_drop_channel_closed_total 438
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7671611
telemt_me_endpoint_quarantine_total 928
telemt_me_single_endpoint_outage_enter_total 24
telemt_me_single_endpoint_outage_exit_total 24
telemt_me_single_endpoint_outage_reconnect_attempt_total 29
telemt_me_single_endpoint_outage_reconnect_success_total 22
telemt_me_single_endpoint_quarantine_bypass_total 29
telemt_me_single_endpoint_shadow_rotate_total 1122
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 40
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 34292
telemt_desync_full_logged_total 11548
telemt_desync_suppressed_total 22744
telemt_desync_frames_bucket_total{bucket="1_2"} 8450
telemt_desync_frames_bucket_total{bucket="3_10"} 13188
telemt_desync_frames_bucket_total{bucket="gt_10"} 12654
telemt_pool_swap_total 158
telemt_pool_force_close_total 4877
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 612
telemt_me_draining_writers_reap_progress_total 47192
telemt_me_writer_removed_unexpected_total 1372
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4288
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 44132
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 15
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4455
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 422
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 42315
telemt_me_writer_teardown_success_total{mode="normal"} 48420
telemt_me_writer_teardown_noop_total 47207
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 89862
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 92558
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 93566
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 94592
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 95275
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 95570
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 95617
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 95619
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 95625
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 95627
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 95627
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 95627
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 95627
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 90.169757
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 95627
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 612
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 1242
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 116
telemt_user_connections_total{user="hello"} 7611180
telemt_user_connections_current{user="hello"} 4410
telemt_user_octets_from_client{user="hello"} 193924068685 (180.61 GB)
telemt_user_octets_to_client{user="hello"} 3438074372778 (3.13 TB)
telemt_user_msgs_from_client{user="hello"} 113340
telemt_user_msgs_to_client{user="hello"} 116189
telemt_user_unique_ips_current{user="hello"} 1721
telemt_user_unique_ips_recent_window{user="hello"} 640
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 147864.9 (41h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9740384
telemt_connections_bad_total 816864
telemt_connections_current 3953
telemt_connections_me_current 3953
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 315315
telemt_upstream_connect_attempt_total 65522
telemt_upstream_connect_success_total 64619
telemt_upstream_connect_fail_total 181
telemt_upstream_connect_attempts_per_request{bucket="1"} 64800
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31051
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30370
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1185
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2013
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 181
telemt_me_keepalive_timeout_total 1383
telemt_me_reconnect_attempts_total 4173
telemt_me_reconnect_success_total 1801
telemt_me_reader_eof_total 1566
telemt_me_idle_close_by_peer_total 1565
telemt_me_route_drop_no_conn_total 4822449
telemt_me_route_drop_channel_closed_total 328
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7351294
telemt_me_endpoint_quarantine_total 1018
telemt_me_single_endpoint_outage_enter_total 28
telemt_me_single_endpoint_outage_exit_total 28
telemt_me_single_endpoint_outage_reconnect_attempt_total 29
telemt_me_single_endpoint_outage_reconnect_success_total 23
telemt_me_single_endpoint_quarantine_bypass_total 29
telemt_me_single_endpoint_shadow_rotate_total 1084
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 54
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 34008
telemt_desync_full_logged_total 11296
telemt_desync_suppressed_total 22712
telemt_desync_frames_bucket_total{bucket="1_2"} 8636
telemt_desync_frames_bucket_total{bucket="3_10"} 13032
telemt_desync_frames_bucket_total{bucket="gt_10"} 12340
telemt_pool_swap_total 154
telemt_pool_force_close_total 4809
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 653
telemt_me_draining_writers_reap_progress_total 47827
telemt_me_writer_removed_unexpected_total 1713
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4789
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 44673
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 21
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4294
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 515
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 43018
telemt_me_writer_teardown_success_total{mode="normal"} 49462
telemt_me_writer_teardown_noop_total 47894
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 92390
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 94740
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 95566
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 96491
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 96973
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 97144
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 97229
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 97248
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 97256
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 97269
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 97302
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 97305
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 97356
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3153.744088
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 97356
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 653
telemt_me_refill_failed_total 122
telemt_me_writer_restored_same_endpoint_total 1571
telemt_me_writer_restored_fallback_total 7
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 56
telemt_me_writer_removed_unexpected_minus_restored_total 135
telemt_user_connections_total{user="hello"} 7345288
telemt_user_connections_current{user="hello"} 3953
telemt_user_octets_from_client{user="hello"} 172369395885 (160.53 GB)
telemt_user_octets_to_client{user="hello"} 3065838024305 (2.79 TB)
telemt_user_msgs_from_client{user="hello"} 46485
telemt_user_msgs_to_client{user="hello"} 113805
telemt_user_unique_ips_current{user="hello"} 1630
telemt_user_unique_ips_recent_window{user="hello"} 614
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 18144.9 (5h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7657382
telemt_connections_bad_total 491408
telemt_connections_current 6551
telemt_connections_me_current 6551
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 121964
telemt_upstream_connect_attempt_total 28016
telemt_upstream_connect_success_total 26651
telemt_upstream_connect_fail_total 1018
telemt_upstream_connect_attempts_per_request{bucket="1"} 27669
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14926
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6464
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 543
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4718
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1018
telemt_me_keepalive_timeout_total 691
telemt_me_reconnect_attempts_total 2689
telemt_me_reconnect_success_total 511
telemt_me_reader_eof_total 316
telemt_me_idle_close_by_peer_total 316
telemt_me_route_drop_no_conn_total 18622551
telemt_me_route_drop_channel_closed_total 27
telemt_me_route_drop_queue_full_total 25
telemt_me_route_drop_queue_full_profile_total{profile="high"} 25
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6366995
telemt_me_endpoint_quarantine_total 115
telemt_me_single_endpoint_outage_enter_total 35
telemt_me_single_endpoint_outage_exit_total 35
telemt_me_single_endpoint_outage_reconnect_attempt_total 61
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 61
telemt_me_single_endpoint_shadow_rotate_total 143
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 56
telemt_desync_total 9295
telemt_desync_full_logged_total 2390
telemt_desync_suppressed_total 6905
telemt_desync_frames_bucket_total{bucket="1_2"} 1662
telemt_desync_frames_bucket_total{bucket="3_10"} 3808
telemt_desync_frames_bucket_total{bucket="gt_10"} 3825
telemt_pool_swap_total 17
telemt_pool_force_close_total 666
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 253
telemt_me_draining_writers_reap_progress_total 4716
telemt_me_writer_removed_unexpected_total 446
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 837
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 4284
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 474
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 192
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 4050
telemt_me_writer_teardown_success_total{mode="normal"} 5121
telemt_me_writer_teardown_noop_total 4719
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 8032
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 8893
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 9249
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 9621
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 9769
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 9836
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 9840
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 9840
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 9840
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 9840
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 9840
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 9840
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 9840
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 21.356839
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 9840
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 253
telemt_me_refill_failed_total 114
telemt_me_writer_restored_same_endpoint_total 348
telemt_me_writer_restored_fallback_total 3
telemt_me_no_writer_failfast_total 86
telemt_me_async_recovery_trigger_total 2805
telemt_me_writer_removed_unexpected_minus_restored_total 95
telemt_user_connections_total{user="hello"} 6382176
telemt_user_connections_current{user="hello"} 6551
telemt_user_octets_from_client{user="hello"} 35766714131 (33.31 GB)
telemt_user_octets_to_client{user="hello"} 187617590436 (174.73 GB)
telemt_user_msgs_from_client{user="hello"} 37295
telemt_user_msgs_to_client{user="hello"} 32778
telemt_user_unique_ips_current{user="hello"} 2407
telemt_user_unique_ips_recent_window{user="hello"} 1832
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 147871.7 (41h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9440972
telemt_connections_bad_total 783902
telemt_connections_current 4020
telemt_connections_me_current 4020
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 203851
telemt_upstream_connect_attempt_total 89827
telemt_upstream_connect_success_total 88923
telemt_upstream_connect_fail_total 782
telemt_upstream_connect_attempts_per_request{bucket="1"} 89705
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 55150
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32313
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 208
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1252
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 782
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 71348
telemt_me_reconnect_success_total 2420
telemt_me_reader_eof_total 2150
telemt_me_idle_close_by_peer_total 2149
telemt_me_route_drop_no_conn_total 4587483
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7454998
telemt_me_endpoint_quarantine_total 996
telemt_me_single_endpoint_outage_enter_total 33
telemt_me_single_endpoint_outage_exit_total 33
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 33
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1107
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 46
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_desync_total 38194
telemt_desync_full_logged_total 13056
telemt_desync_suppressed_total 25138
telemt_desync_frames_bucket_total{bucket="1_2"} 7753
telemt_desync_frames_bucket_total{bucket="3_10"} 14774
telemt_desync_frames_bucket_total{bucket="gt_10"} 15667
telemt_pool_swap_total 152
telemt_pool_force_close_total 4500
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 547
telemt_me_draining_writers_reap_progress_total 50475
telemt_me_writer_removed_unexpected_total 2177
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5336
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 47333
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3885
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 615
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 45975
telemt_me_writer_teardown_success_total{mode="normal"} 52669
telemt_me_writer_teardown_noop_total 50476
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 101328
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 102477
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 102837
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 103101
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 103135
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 103138
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 103138
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 103141
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 103145
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 103145
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 103145
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 103145
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 103145
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 15.715888
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 103145
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 547
telemt_me_refill_failed_total 4253
telemt_me_writer_restored_same_endpoint_total 2028
telemt_me_writer_restored_fallback_total 42
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7358
telemt_me_writer_removed_unexpected_minus_restored_total 107
telemt_user_connections_total{user="hello"} 7456293
telemt_user_connections_current{user="hello"} 4020
telemt_user_octets_from_client{user="hello"} 172150309519 (160.33 GB)
telemt_user_octets_to_client{user="hello"} 2841314783749 (2.58 TB)
telemt_user_msgs_from_client{user="hello"} 146235
telemt_user_msgs_to_client{user="hello"} 572261
telemt_user_unique_ips_current{user="hello"} 1504
telemt_user_unique_ips_recent_window{user="hello"} 720
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 84707.8 (23h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9384463
telemt_connections_bad_total 335872
telemt_connections_current 5425
telemt_connections_me_current 5425
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 3946737
telemt_upstream_connect_attempt_total 42056
telemt_upstream_connect_success_total 41750
telemt_upstream_connect_fail_total 298
telemt_upstream_connect_attempts_per_request{bucket="1"} 42048
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23902
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17733
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 115
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 298
telemt_me_reconnect_attempts_total 47904
telemt_me_reconnect_success_total 1435
telemt_me_reader_eof_total 1102
telemt_me_idle_close_by_peer_total 1102
telemt_me_route_drop_no_conn_total 3418456
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4522045
telemt_me_endpoint_quarantine_total 558
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 58
telemt_me_single_endpoint_outage_reconnect_success_total 18
telemt_me_single_endpoint_quarantine_bypass_total 58
telemt_me_single_endpoint_shadow_rotate_total 635
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 24748
telemt_desync_full_logged_total 8296
telemt_desync_suppressed_total 16452
telemt_desync_frames_bucket_total{bucket="1_2"} 4998
telemt_desync_frames_bucket_total{bucket="3_10"} 9771
telemt_desync_frames_bucket_total{bucket="gt_10"} 9979
telemt_pool_swap_total 89
telemt_pool_force_close_total 2739
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 284
telemt_me_draining_writers_reap_progress_total 29426
telemt_me_writer_removed_unexpected_total 1167
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2659
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27962
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2333
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 406
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26687
telemt_me_writer_teardown_success_total{mode="normal"} 30621
telemt_me_writer_teardown_noop_total 29433
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 59066
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 59614
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 59846
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 60054
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 60054
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 60054
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 60054
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 60054
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 60054
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 60054
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 60054
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 60054
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 60054
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.044699
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 60054
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 284
telemt_me_refill_failed_total 2701
telemt_me_writer_restored_same_endpoint_total 1282
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4328
telemt_user_connections_total{user="hello"} 4516785
telemt_user_connections_current{user="hello"} 5425
telemt_user_octets_from_client{user="hello"} 99422071004 (92.59 GB)
telemt_user_octets_to_client{user="hello"} 1731244675410 (1.57 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 2237
telemt_user_unique_ips_recent_window{user="hello"} 644
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 65678.7 (18h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 774072
telemt_connections_bad_total 9751
telemt_connections_current 1017
telemt_connections_me_current 1017
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 14755
telemt_upstream_connect_attempt_total 33303
telemt_upstream_connect_success_total 33219
telemt_upstream_connect_fail_total 69
telemt_upstream_connect_attempts_per_request{bucket="1"} 33288
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15225
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17579
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 415
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 69
telemt_me_reconnect_attempts_total 1466
telemt_me_reconnect_success_total 633
telemt_me_reader_eof_total 616
telemt_me_idle_close_by_peer_total 616
telemt_me_route_drop_no_conn_total 260539
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 694749
telemt_me_endpoint_quarantine_total 584
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 547
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 46
telemt_desync_total 3849
telemt_desync_full_logged_total 1153
telemt_desync_suppressed_total 2696
telemt_desync_frames_bucket_total{bucket="1_2"} 939
telemt_desync_frames_bucket_total{bucket="3_10"} 1534
telemt_desync_frames_bucket_total{bucket="gt_10"} 1376
telemt_pool_swap_total 69
telemt_pool_force_close_total 1707
telemt_me_writer_close_signal_drop_total 98
telemt_me_draining_writers_reap_progress_total 27346
telemt_me_writer_removed_unexpected_total 595
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2090
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 25874
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1630
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 77
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 25639
telemt_me_writer_teardown_success_total{mode="normal"} 27964
telemt_me_writer_teardown_noop_total 27348
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 54757
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 55175
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 55287
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 55312
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 55312
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 55312
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 55312
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 55312
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 55312
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 55312
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 55312
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 55312
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 55312
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.011830
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 55312
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 98
telemt_me_refill_failed_total 45
telemt_me_writer_restored_same_endpoint_total 550
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 36
telemt_user_connections_total{user="hello"} 696244
telemt_user_connections_current{user="hello"} 1017
telemt_user_octets_from_client{user="hello"} 13086317637 (12.19 GB)
telemt_user_octets_to_client{user="hello"} 329149191463 (306.54 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 371
telemt_user_unique_ips_recent_window{user="hello"} 150
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 147876.1 (41h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11530378
telemt_connections_bad_total 1349458
telemt_connections_current 5858
telemt_connections_me_current 5858
telemt_handshake_timeouts_total 313142
telemt_upstream_connect_attempt_total 55808
telemt_upstream_connect_success_total 55592
telemt_upstream_connect_fail_total 168
telemt_upstream_connect_attempts_per_request{bucket="1"} 55760
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27404
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28141
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 168
telemt_me_reconnect_attempts_total 2188
telemt_me_reconnect_success_total 1164
telemt_me_reader_eof_total 1129
telemt_me_idle_close_by_peer_total 1129
telemt_me_route_drop_no_conn_total 3646576
telemt_me_route_drop_channel_closed_total 99
telemt_me_route_drop_queue_full_total 32
telemt_me_route_drop_queue_full_profile_total{profile="high"} 32
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8663744
telemt_me_endpoint_quarantine_total 1016
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 12
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 12
telemt_me_single_endpoint_shadow_rotate_total 1110
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 40
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_desync_total 35539
telemt_desync_full_logged_total 11648
telemt_desync_suppressed_total 23891
telemt_desync_frames_bucket_total{bucket="1_2"} 8466
telemt_desync_frames_bucket_total{bucket="3_10"} 13168
telemt_desync_frames_bucket_total{bucket="gt_10"} 13905
telemt_pool_swap_total 164
telemt_pool_force_close_total 4516
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 565
telemt_me_draining_writers_reap_progress_total 50286
telemt_me_writer_removed_unexpected_total 1084
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4122
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 47278
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4362
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 154
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 45770
telemt_me_writer_teardown_success_total{mode="normal"} 51400
telemt_me_writer_teardown_noop_total 50288
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 99581
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 101002
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 101293
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 101582
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 101684
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 101688
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 101688
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 101688
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 101688
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 101688
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 101688
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 101688
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 101688
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 15.437421
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 101688
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 565
telemt_me_refill_failed_total 53
telemt_me_writer_restored_same_endpoint_total 1020
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 8634259
telemt_user_connections_current{user="hello"} 5858
telemt_user_octets_from_client{user="hello"} 166843231936 (155.38 GB)
telemt_user_octets_to_client{user="hello"} 3889653460000 (3.54 TB)
telemt_user_unique_ips_current{user="hello"} 2079
telemt_user_unique_ips_recent_window{user="hello"} 779
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 147872.9 (41h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9950171
telemt_connections_bad_total 1113978
telemt_connections_current 4576
telemt_connections_me_current 4576
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 260770
telemt_upstream_connect_attempt_total 81397
telemt_upstream_connect_success_total 80800
telemt_upstream_connect_fail_total 516
telemt_upstream_connect_attempts_per_request{bucket="1"} 81316
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44698
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33185
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 909
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2008
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 516
telemt_me_reconnect_attempts_total 8570
telemt_me_reconnect_success_total 1936
telemt_me_reader_eof_total 1805
telemt_me_idle_close_by_peer_total 1805
telemt_me_seq_mismatch_total 72
telemt_me_route_drop_no_conn_total 4461019
telemt_me_route_drop_channel_closed_total 317
telemt_me_route_drop_queue_full_total 16
telemt_me_route_drop_queue_full_profile_total{profile="high"} 16
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7659589
telemt_me_endpoint_quarantine_total 1134
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 35
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 1111
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 45
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 46
telemt_desync_total 34768
telemt_desync_full_logged_total 11320
telemt_desync_suppressed_total 23448
telemt_desync_frames_bucket_total{bucket="1_2"} 8589
telemt_desync_frames_bucket_total{bucket="3_10"} 12948
telemt_desync_frames_bucket_total{bucket="gt_10"} 13231
telemt_pool_swap_total 157
telemt_pool_force_close_total 4374
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 562
telemt_me_draining_writers_reap_progress_total 49608
telemt_me_writer_removed_unexpected_total 1830
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5139
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 46366
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3976
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 398
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 45234
telemt_me_writer_teardown_success_total{mode="normal"} 51505
telemt_me_writer_teardown_noop_total 49612
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 98783
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 100314
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 100795
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 101067
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 101117
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 101117
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 101117
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 101117
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 101117
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 101117
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 101117
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 101117
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 101117
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 15.272878
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 101117
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 562
telemt_me_refill_failed_total 340
telemt_me_writer_restored_same_endpoint_total 1574
telemt_me_writer_restored_fallback_total 96
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 128
telemt_me_writer_removed_unexpected_minus_restored_total 160
telemt_user_connections_total{user="hello"} 7666619
telemt_user_connections_current{user="hello"} 4576
telemt_user_octets_from_client{user="hello"} 135567436137 (126.26 GB)
telemt_user_octets_to_client{user="hello"} 3021961028587 (2.75 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 1778
telemt_user_unique_ips_recent_window{user="hello"} 670
```