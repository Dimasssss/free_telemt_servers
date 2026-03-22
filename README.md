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

# Server Metrics 2026-03-22 12:07:56 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 54093.8 (15h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1602750
telemt_connections_bad_total 75845
telemt_connections_current 1769
telemt_connections_me_current 1769
telemt_handshake_timeouts_total 71923
telemt_upstream_connect_attempt_total 20640
telemt_upstream_connect_success_total 20639
telemt_upstream_connect_attempts_per_request{bucket="1"} 20639
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7103
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13472
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 51
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 754
telemt_me_reconnect_success_total 339
telemt_me_reader_eof_total 336
telemt_me_idle_close_by_peer_total 336
telemt_me_route_drop_no_conn_total 1089192
telemt_me_route_drop_channel_closed_total 479
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1355658
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_endpoint_quarantine_total 379
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 431
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 14
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
telemt_me_writers_warm_current 40
telemt_desync_total 8093
telemt_desync_full_logged_total 2429
telemt_desync_suppressed_total 5664
telemt_desync_frames_bucket_total{bucket="1_2"} 2303
telemt_desync_frames_bucket_total{bucket="3_10"} 3049
telemt_desync_frames_bucket_total{bucket="gt_10"} 2741
telemt_pool_swap_total 59
telemt_pool_force_close_total 1762
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 275
telemt_me_draining_writers_reap_progress_total 18777
telemt_me_writer_removed_unexpected_total 331
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1314
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17672
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1727
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 35
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17015
telemt_me_writer_teardown_success_total{mode="normal"} 18986
telemt_me_writer_teardown_noop_total 18779
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 32337
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 33469
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 34437
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 35978
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 37099
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 37627
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 37762
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 37765
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 37765
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 37765
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 37765
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 37765
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 37765
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 132.973892
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 37765
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 275
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 302
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 1352994
telemt_user_connections_current{user="hello"} 1769
telemt_user_octets_from_client{user="hello"} 21157802900 (19.70 GB)
telemt_user_octets_to_client{user="hello"} 401377645652 (373.81 GB)
telemt_user_unique_ips_current{user="hello"} 677
telemt_user_unique_ips_recent_window{user="hello"} 261
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 67459.5 (18h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2588740
telemt_connections_bad_total 229485
telemt_connections_current 2210
telemt_connections_me_current 2210
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 59687
telemt_upstream_connect_attempt_total 44600
telemt_upstream_connect_success_total 44083
telemt_upstream_connect_fail_total 457
telemt_upstream_connect_attempts_per_request{bucket="1"} 44540
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26901
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17066
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 116
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 457
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 3405
telemt_me_reconnect_success_total 1516
telemt_me_reader_eof_total 1398
telemt_me_idle_close_by_peer_total 1398
telemt_me_route_drop_no_conn_total 2261901
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2034145
telemt_me_endpoint_quarantine_total 573
telemt_me_single_endpoint_outage_enter_total 31
telemt_me_single_endpoint_outage_exit_total 31
telemt_me_single_endpoint_outage_reconnect_attempt_total 31
telemt_me_single_endpoint_outage_reconnect_success_total 31
telemt_me_single_endpoint_quarantine_bypass_total 31
telemt_me_single_endpoint_shadow_rotate_total 528
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 30
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
telemt_desync_total 8044
telemt_desync_full_logged_total 4535
telemt_desync_suppressed_total 3509
telemt_desync_frames_bucket_total{bucket="1_2"} 1869
telemt_desync_frames_bucket_total{bucket="3_10"} 3131
telemt_desync_frames_bucket_total{bucket="gt_10"} 3044
telemt_pool_swap_total 67
telemt_pool_force_close_total 1890
telemt_me_writer_close_signal_drop_total 157
telemt_me_draining_writers_reap_progress_total 26820
telemt_me_writer_removed_unexpected_total 1360
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2940
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 25238
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1680
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 210
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 24930
telemt_me_writer_teardown_success_total{mode="normal"} 28178
telemt_me_writer_teardown_noop_total 26820
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 53806
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 54530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 54751
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 54977
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 54995
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 54998
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 54998
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 54998
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 54998
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 54998
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 54998
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 54998
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 54998
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.292326
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 54998
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 157
telemt_me_refill_failed_total 85
telemt_me_writer_restored_same_endpoint_total 1259
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 21
telemt_me_writer_removed_unexpected_minus_restored_total 79
telemt_user_connections_total{user="hello"} 2045943
telemt_user_connections_current{user="hello"} 2210
telemt_user_octets_from_client{user="hello"} 25475099455 (23.73 GB)
telemt_user_octets_to_client{user="hello"} 501090339614 (466.68 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 1306
telemt_user_unique_ips_recent_window{user="hello"} 827
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 142319.8 (39h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12671704
telemt_connections_bad_total 1104182
telemt_connections_current 4296
telemt_connections_me_current 4296
telemt_handshake_timeouts_total 329593
telemt_upstream_connect_attempt_total 51942
telemt_upstream_connect_success_total 51861
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 51869
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23464
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28175
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 216
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2280
telemt_me_reconnect_success_total 1191
telemt_me_reader_eof_total 1164
telemt_me_idle_close_by_peer_total 1163
telemt_me_route_drop_no_conn_total 10354593
telemt_me_route_drop_channel_closed_total 114
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10125537
telemt_me_endpoint_quarantine_total 901
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 1060
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
telemt_me_writers_active_current 44
telemt_desync_total 41533
telemt_desync_full_logged_total 13298
telemt_desync_suppressed_total 28235
telemt_desync_frames_bucket_total{bucket="1_2"} 9357
telemt_desync_frames_bucket_total{bucket="3_10"} 16233
telemt_desync_frames_bucket_total{bucket="gt_10"} 15943
telemt_pool_swap_total 153
telemt_pool_force_close_total 5197
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 820
telemt_me_draining_writers_reap_progress_total 47351
telemt_me_writer_removed_unexpected_total 1123
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4096
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 43746
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4787
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 410
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 42154
telemt_me_writer_teardown_success_total{mode="normal"} 47842
telemt_me_writer_teardown_noop_total 47399
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 86536
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 89297
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 90675
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 92614
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 94000
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 94806
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 95229
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 95241
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 95241
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 95241
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 95241
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 95241
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 95241
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 225.182858
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 95241
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 820
telemt_me_refill_failed_total 59
telemt_me_writer_restored_same_endpoint_total 1042
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 74
telemt_user_connections_total{user="hello"} 10114106
telemt_user_connections_current{user="hello"} 4296
telemt_user_octets_from_client{user="hello"} 149902633444 (139.61 GB)
telemt_user_octets_to_client{user="hello"} 2826434464136 (2.57 TB)
telemt_user_unique_ips_current{user="hello"} 1592
telemt_user_unique_ips_recent_window{user="hello"} 1662
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 142320.8 (39h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9566503
telemt_connections_bad_total 865496
telemt_connections_current 4668
telemt_connections_me_current 4668
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 288619
telemt_upstream_connect_attempt_total 78289
telemt_upstream_connect_success_total 77164
telemt_upstream_connect_fail_total 811
telemt_upstream_connect_attempts_per_request{bucket="1"} 77975
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 42622
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30717
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 156
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3669
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 811
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 182
telemt_me_reconnect_attempts_total 3324
telemt_me_reconnect_success_total 1350
telemt_me_reader_eof_total 1234
telemt_me_idle_close_by_peer_total 1234
telemt_me_route_drop_no_conn_total 3834399
telemt_me_route_drop_channel_closed_total 395
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7133016
telemt_me_endpoint_quarantine_total 900
telemt_me_single_endpoint_outage_enter_total 22
telemt_me_single_endpoint_outage_exit_total 22
telemt_me_single_endpoint_outage_reconnect_attempt_total 27
telemt_me_single_endpoint_outage_reconnect_success_total 20
telemt_me_single_endpoint_quarantine_bypass_total 27
telemt_me_single_endpoint_shadow_rotate_total 1085
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
telemt_me_writers_active_current 43
telemt_desync_total 32180
telemt_desync_full_logged_total 10901
telemt_desync_suppressed_total 21279
telemt_desync_frames_bucket_total{bucket="1_2"} 7918
telemt_desync_frames_bucket_total{bucket="3_10"} 12386
telemt_desync_frames_bucket_total{bucket="gt_10"} 11876
telemt_pool_swap_total 153
telemt_pool_force_close_total 4641
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 567
telemt_me_draining_writers_reap_progress_total 45628
telemt_me_writer_removed_unexpected_total 1266
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4065
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 42696
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4265
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 376
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 40987
telemt_me_writer_teardown_success_total{mode="normal"} 46761
telemt_me_writer_teardown_noop_total 45636
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 87135
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 89642
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 90563
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 91484
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 92096
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 92358
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 92387
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 92389
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 92395
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 92397
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 92397
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 92397
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 92397
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 80.312703
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 92397
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 567
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 1151
telemt_me_writer_restored_fallback_total 12
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 212
telemt_me_writer_removed_unexpected_minus_restored_total 103
telemt_user_connections_total{user="hello"} 7073695
telemt_user_connections_current{user="hello"} 4668
telemt_user_octets_from_client{user="hello"} 183060076853 (170.49 GB)
telemt_user_octets_to_client{user="hello"} 3223404658546 (2.93 TB)
telemt_user_msgs_from_client{user="hello"} 113340
telemt_user_msgs_to_client{user="hello"} 116189
telemt_user_unique_ips_current{user="hello"} 1862
telemt_user_unique_ips_recent_window{user="hello"} 741
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 142284.8 (39h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9038565
telemt_connections_bad_total 758764
telemt_connections_current 4776
telemt_connections_me_current 4776
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 285434
telemt_upstream_connect_attempt_total 62576
telemt_upstream_connect_success_total 61842
telemt_upstream_connect_fail_total 147
telemt_upstream_connect_attempts_per_request{bucket="1"} 61989
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30130
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29243
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1054
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1415
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 147
telemt_me_keepalive_timeout_total 238
telemt_me_reconnect_attempts_total 3794
telemt_me_reconnect_success_total 1599
telemt_me_reader_eof_total 1481
telemt_me_idle_close_by_peer_total 1481
telemt_me_route_drop_no_conn_total 3926604
telemt_me_route_drop_channel_closed_total 268
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6807811
telemt_me_endpoint_quarantine_total 972
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 19
telemt_me_single_endpoint_outage_reconnect_success_total 15
telemt_me_single_endpoint_quarantine_bypass_total 19
telemt_me_single_endpoint_shadow_rotate_total 1038
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 52
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
telemt_me_writers_warm_current 23
telemt_desync_total 31889
telemt_desync_full_logged_total 10669
telemt_desync_suppressed_total 21220
telemt_desync_frames_bucket_total{bucket="1_2"} 8021
telemt_desync_frames_bucket_total{bucket="3_10"} 12234
telemt_desync_frames_bucket_total{bucket="gt_10"} 11634
telemt_pool_swap_total 148
telemt_pool_force_close_total 4585
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 553
telemt_me_draining_writers_reap_progress_total 46367
telemt_me_writer_removed_unexpected_total 1513
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4441
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 43377
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 20
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4111
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 474
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 41782
telemt_me_writer_teardown_success_total{mode="normal"} 47818
telemt_me_writer_teardown_noop_total 46387
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 89808
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 91962
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 92736
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 93572
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 93994
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 94140
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 94201
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 94203
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 94205
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 94205
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 94205
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 94205
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 94205
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 59.700900
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 94205
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 553
telemt_me_refill_failed_total 113
telemt_me_writer_restored_same_endpoint_total 1416
telemt_me_writer_restored_fallback_total 7
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 50
telemt_me_writer_removed_unexpected_minus_restored_total 90
telemt_user_connections_total{user="hello"} 6798774
telemt_user_connections_current{user="hello"} 4776
telemt_user_octets_from_client{user="hello"} 165094422419 (153.76 GB)
telemt_user_octets_to_client{user="hello"} 2917717942659 (2.65 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 1853
telemt_user_unique_ips_recent_window{user="hello"} 657
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 12564.6 (3h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5333510
telemt_connections_bad_total 322171
telemt_connections_current 6649
telemt_connections_me_current 6649
telemt_relay_adaptive_promotions_total 7
telemt_relay_adaptive_hard_promotions_total 7
telemt_handshake_timeouts_total 83672
telemt_upstream_connect_attempt_total 23704
telemt_upstream_connect_success_total 22646
telemt_upstream_connect_fail_total 835
telemt_upstream_connect_attempts_per_request{bucket="1"} 23481
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13058
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4702
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 262
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4624
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 835
telemt_me_keepalive_timeout_total 508
telemt_me_reconnect_attempts_total 2286
telemt_me_reconnect_success_total 349
telemt_me_reader_eof_total 219
telemt_me_idle_close_by_peer_total 219
telemt_me_route_drop_no_conn_total 12375535
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 24
telemt_me_route_drop_queue_full_profile_total{profile="high"} 24
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4467689
telemt_me_endpoint_quarantine_total 84
telemt_me_single_endpoint_outage_enter_total 22
telemt_me_single_endpoint_outage_exit_total 22
telemt_me_single_endpoint_outage_reconnect_attempt_total 39
telemt_me_single_endpoint_outage_reconnect_success_total 12
telemt_me_single_endpoint_quarantine_bypass_total 39
telemt_me_single_endpoint_shadow_rotate_total 103
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 10
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
telemt_desync_total 6718
telemt_desync_full_logged_total 1722
telemt_desync_suppressed_total 4996
telemt_desync_frames_bucket_total{bucket="1_2"} 1232
telemt_desync_frames_bucket_total{bucket="3_10"} 2682
telemt_desync_frames_bucket_total{bucket="gt_10"} 2804
telemt_pool_swap_total 11
telemt_pool_force_close_total 473
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 193
telemt_me_draining_writers_reap_progress_total 3261
telemt_me_writer_removed_unexpected_total 308
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 572
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 2953
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 335
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 138
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 2788
telemt_me_writer_teardown_success_total{mode="normal"} 3525
telemt_me_writer_teardown_noop_total 3264
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 5470
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 6076
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 6347
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 6627
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 6736
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 6788
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 6789
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 6789
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 6789
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 6789
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 6789
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 6789
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 6789
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 15.850534
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 6789
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 193
telemt_me_refill_failed_total 107
telemt_me_writer_restored_same_endpoint_total 234
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 204
telemt_me_writer_removed_unexpected_minus_restored_total 71
telemt_user_connections_total{user="hello"} 4481317
telemt_user_connections_current{user="hello"} 6649
telemt_user_octets_from_client{user="hello"} 24544311554 (22.86 GB)
telemt_user_octets_to_client{user="hello"} 130494684483 (121.53 GB)
telemt_user_msgs_from_client{user="hello"} 33078
telemt_user_msgs_to_client{user="hello"} 29827
telemt_user_unique_ips_current{user="hello"} 2433
telemt_user_unique_ips_recent_window{user="hello"} 1395
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 142291.7 (39h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8770338
telemt_connections_bad_total 747791
telemt_connections_current 5391
telemt_connections_me_current 5391
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 185443
telemt_upstream_connect_attempt_total 87842
telemt_upstream_connect_success_total 86972
telemt_upstream_connect_fail_total 748
telemt_upstream_connect_attempts_per_request{bucket="1"} 87720
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 54254
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31265
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 208
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1245
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 748
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 70766
telemt_me_reconnect_success_total 2265
telemt_me_reader_eof_total 1996
telemt_me_idle_close_by_peer_total 1995
telemt_me_route_drop_no_conn_total 4044362
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 45
telemt_me_route_drop_queue_full_profile_total{profile="high"} 45
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6930755
telemt_me_endpoint_quarantine_total 945
telemt_me_single_endpoint_outage_enter_total 30
telemt_me_single_endpoint_outage_exit_total 30
telemt_me_single_endpoint_outage_reconnect_attempt_total 32
telemt_me_single_endpoint_outage_reconnect_success_total 30
telemt_me_single_endpoint_quarantine_bypass_total 32
telemt_me_single_endpoint_shadow_rotate_total 1064
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
telemt_me_writers_active_current 90
telemt_me_writers_warm_current 20
telemt_desync_total 35422
telemt_desync_full_logged_total 12202
telemt_desync_suppressed_total 23220
telemt_desync_frames_bucket_total{bucket="1_2"} 7236
telemt_desync_frames_bucket_total{bucket="3_10"} 13609
telemt_desync_frames_bucket_total{bucket="gt_10"} 14577
telemt_pool_swap_total 146
telemt_pool_force_close_total 4253
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 516
telemt_me_draining_writers_reap_progress_total 48729
telemt_me_writer_removed_unexpected_total 2025
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5050
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 45729
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3708
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 545
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 44476
telemt_me_writer_teardown_success_total{mode="normal"} 50779
telemt_me_writer_teardown_noop_total 48730
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 97819
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 98896
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 99225
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 99468
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 99499
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 99502
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 99502
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 99505
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 99509
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 99509
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 99509
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 99509
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 99509
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.849899
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 99509
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 516
telemt_me_refill_failed_total 4235
telemt_me_writer_restored_same_endpoint_total 1888
telemt_me_writer_restored_fallback_total 41
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7333
telemt_me_writer_removed_unexpected_minus_restored_total 96
telemt_user_connections_total{user="hello"} 6933582
telemt_user_connections_current{user="hello"} 5391
telemt_user_octets_from_client{user="hello"} 164660138719 (153.35 GB)
telemt_user_octets_to_client{user="hello"} 2693259994617 (2.45 TB)
telemt_user_msgs_from_client{user="hello"} 146235
telemt_user_msgs_to_client{user="hello"} 572261
telemt_user_unique_ips_current{user="hello"} 2194
telemt_user_unique_ips_recent_window{user="hello"} 754
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 79127.5 (21h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8190922
telemt_connections_bad_total 291523
telemt_connections_current 4282
telemt_connections_me_current 4282
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 3412929
telemt_upstream_connect_attempt_total 40109
telemt_upstream_connect_success_total 39821
telemt_upstream_connect_fail_total 281
telemt_upstream_connect_attempts_per_request{bucket="1"} 40102
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23041
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16672
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 108
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 281
telemt_me_reconnect_attempts_total 47797
telemt_me_reconnect_success_total 1351
telemt_me_reader_eof_total 1019
telemt_me_idle_close_by_peer_total 1019
telemt_me_route_drop_no_conn_total 2735040
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4000406
telemt_me_endpoint_quarantine_total 533
telemt_me_single_endpoint_outage_enter_total 17
telemt_me_single_endpoint_outage_exit_total 17
telemt_me_single_endpoint_outage_reconnect_attempt_total 57
telemt_me_single_endpoint_outage_reconnect_success_total 17
telemt_me_single_endpoint_quarantine_bypass_total 57
telemt_me_single_endpoint_shadow_rotate_total 600
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 20
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
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 21977
telemt_desync_full_logged_total 7361
telemt_desync_suppressed_total 14616
telemt_desync_frames_bucket_total{bucket="1_2"} 4498
telemt_desync_frames_bucket_total{bucket="3_10"} 8534
telemt_desync_frames_bucket_total{bucket="gt_10"} 8945
telemt_pool_swap_total 83
telemt_pool_force_close_total 2550
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 256
telemt_me_draining_writers_reap_progress_total 27723
telemt_me_writer_removed_unexpected_total 1086
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2471
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26364
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2186
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 364
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 25173
telemt_me_writer_teardown_success_total{mode="normal"} 28835
telemt_me_writer_teardown_noop_total 27730
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 55676
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 56183
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 56408
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 56565
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 56565
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 56565
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 56565
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 56565
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 56565
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 56565
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 56565
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 56565
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 56565
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.732701
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 56565
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 256
telemt_me_refill_failed_total 2700
telemt_me_writer_restored_same_endpoint_total 1203
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4328
telemt_user_connections_total{user="hello"} 3997501
telemt_user_connections_current{user="hello"} 4282
telemt_user_octets_from_client{user="hello"} 90854003144 (84.61 GB)
telemt_user_octets_to_client{user="hello"} 1585213945354 (1.44 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 1661
telemt_user_unique_ips_recent_window{user="hello"} 759
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 60098.3 (16h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 660197
telemt_connections_bad_total 7082
telemt_connections_current 983
telemt_connections_me_current 983
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 12722
telemt_upstream_connect_attempt_total 31057
telemt_upstream_connect_success_total 30981
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 31046
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14317
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16313
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 351
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_reconnect_attempts_total 1388
telemt_me_reconnect_success_total 598
telemt_me_reader_eof_total 578
telemt_me_idle_close_by_peer_total 578
telemt_me_route_drop_no_conn_total 220408
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 595814
telemt_me_endpoint_quarantine_total 547
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 505
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 13
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
telemt_desync_total 3282
telemt_desync_full_logged_total 955
telemt_desync_suppressed_total 2327
telemt_desync_frames_bucket_total{bucket="1_2"} 830
telemt_desync_frames_bucket_total{bucket="3_10"} 1293
telemt_desync_frames_bucket_total{bucket="gt_10"} 1159
telemt_pool_swap_total 63
telemt_pool_force_close_total 1544
telemt_me_writer_close_signal_drop_total 84
telemt_me_draining_writers_reap_progress_total 25359
telemt_me_writer_removed_unexpected_total 560
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1922
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 24016
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1467
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 77
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 23815
telemt_me_writer_teardown_success_total{mode="normal"} 25938
telemt_me_writer_teardown_noop_total 25361
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 50792
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 51173
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 51274
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 51299
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 51299
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 51299
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 51299
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 51299
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 51299
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 51299
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 51299
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 51299
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 51299
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.763238
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 51299
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 84
telemt_me_refill_failed_total 43
telemt_me_writer_restored_same_endpoint_total 520
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 34
telemt_user_connections_total{user="hello"} 597625
telemt_user_connections_current{user="hello"} 983
telemt_user_octets_from_client{user="hello"} 11385815957 (10.60 GB)
telemt_user_octets_to_client{user="hello"} 281460577939 (262.13 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 369
telemt_user_unique_ips_recent_window{user="hello"} 159
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 142297.1 (39h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10651396
telemt_connections_bad_total 1241778
telemt_connections_current 6365
telemt_connections_me_current 6365
telemt_handshake_timeouts_total 284337
telemt_upstream_connect_attempt_total 54216
telemt_upstream_connect_success_total 54005
telemt_upstream_connect_fail_total 163
telemt_upstream_connect_attempts_per_request{bucket="1"} 54168
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26651
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27308
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 163
telemt_me_reconnect_attempts_total 2117
telemt_me_reconnect_success_total 1130
telemt_me_reader_eof_total 1092
telemt_me_idle_close_by_peer_total 1092
telemt_me_route_drop_no_conn_total 3185576
telemt_me_route_drop_channel_closed_total 83
telemt_me_route_drop_queue_full_total 31
telemt_me_route_drop_queue_full_profile_total{profile="high"} 31
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7975323
telemt_me_endpoint_quarantine_total 986
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 12
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 12
telemt_me_single_endpoint_shadow_rotate_total 1068
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
telemt_me_writers_active_current 50
telemt_me_writers_warm_current 38
telemt_desync_total 32573
telemt_desync_full_logged_total 10725
telemt_desync_suppressed_total 21848
telemt_desync_frames_bucket_total{bucket="1_2"} 7871
telemt_desync_frames_bucket_total{bucket="3_10"} 12003
telemt_desync_frames_bucket_total{bucket="gt_10"} 12699
telemt_pool_swap_total 157
telemt_pool_force_close_total 4284
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 531
telemt_me_draining_writers_reap_progress_total 48821
telemt_me_writer_removed_unexpected_total 1048
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3972
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 45932
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4147
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 137
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 44537
telemt_me_writer_teardown_success_total{mode="normal"} 49904
telemt_me_writer_teardown_noop_total 48823
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 96819
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 98113
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 98368
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 98623
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 98723
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 98727
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 98727
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 98727
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 98727
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 98727
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 98727
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 98727
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 98727
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.215569
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 98727
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 531
telemt_me_refill_failed_total 51
telemt_me_writer_restored_same_endpoint_total 987
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 50
telemt_user_connections_total{user="hello"} 7946603
telemt_user_connections_current{user="hello"} 6365
telemt_user_octets_from_client{user="hello"} 153248083828 (142.72 GB)
telemt_user_octets_to_client{user="hello"} 3649224026012 (3.32 TB)
telemt_user_unique_ips_current{user="hello"} 2109
telemt_user_unique_ips_recent_window{user="hello"} 1025
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 142293.1 (39h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9311806
telemt_connections_bad_total 1052118
telemt_connections_current 5232
telemt_connections_me_current 5232
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 240690
telemt_upstream_connect_attempt_total 78955
telemt_upstream_connect_success_total 78379
telemt_upstream_connect_fail_total 501
telemt_upstream_connect_attempts_per_request{bucket="1"} 78880
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43592
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31901
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 909
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1977
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 501
telemt_me_reconnect_attempts_total 6710
telemt_me_reconnect_success_total 1641
telemt_me_reader_eof_total 1461
telemt_me_idle_close_by_peer_total 1461
telemt_me_seq_mismatch_total 69
telemt_me_route_drop_no_conn_total 3765196
telemt_me_route_drop_channel_closed_total 288
telemt_me_route_drop_queue_full_total 15
telemt_me_route_drop_queue_full_profile_total{profile="high"} 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7146273
telemt_me_endpoint_quarantine_total 1096
telemt_me_single_endpoint_outage_enter_total 35
telemt_me_single_endpoint_outage_exit_total 35
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 33
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1075
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 43
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
telemt_me_writers_active_current 90
telemt_me_writers_warm_current 26
telemt_desync_total 31853
telemt_desync_full_logged_total 10410
telemt_desync_suppressed_total 21443
telemt_desync_frames_bucket_total{bucket="1_2"} 7876
telemt_desync_frames_bucket_total{bucket="3_10"} 11836
telemt_desync_frames_bucket_total{bucket="gt_10"} 12141
telemt_pool_swap_total 153
telemt_pool_force_close_total 4179
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 522
telemt_me_draining_writers_reap_progress_total 47634
telemt_me_writer_removed_unexpected_total 1482
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4663
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 44518
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3866
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 313
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 43455
telemt_me_writer_teardown_success_total{mode="normal"} 49181
telemt_me_writer_teardown_noop_total 47638
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 94628
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 96054
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 96521
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 96781
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 96819
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 96819
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 96819
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 96819
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 96819
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 96819
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 96819
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 96819
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 96819
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.162273
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 96819
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 522
telemt_me_refill_failed_total 291
telemt_me_writer_restored_same_endpoint_total 1289
telemt_me_writer_restored_fallback_total 93
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 128
telemt_me_writer_removed_unexpected_minus_restored_total 100
telemt_user_connections_total{user="hello"} 7154177
telemt_user_connections_current{user="hello"} 5232
telemt_user_octets_from_client{user="hello"} 127303422201 (118.56 GB)
telemt_user_octets_to_client{user="hello"} 2896254045563 (2.63 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 2127
telemt_user_unique_ips_recent_window{user="hello"} 889
```