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

# Server Metrics 2026-03-22 08:54:01 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 42458.5 (11h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1027024
telemt_connections_bad_total 58245
telemt_connections_current 1548
telemt_connections_me_current 1548
telemt_handshake_timeouts_total 47152
telemt_upstream_connect_attempt_total 16819
telemt_upstream_connect_success_total 16818
telemt_upstream_connect_attempts_per_request{bucket="1"} 16818
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5862
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10906
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 39
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 486
telemt_me_reconnect_success_total 260
telemt_me_reader_eof_total 258
telemt_me_idle_close_by_peer_total 258
telemt_me_route_drop_no_conn_total 565055
telemt_me_route_drop_channel_closed_total 186
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 854830
telemt_me_endpoint_quarantine_total 303
telemt_me_single_endpoint_shadow_rotate_total 343
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 9
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
telemt_desync_total 6322
telemt_desync_full_logged_total 1781
telemt_desync_suppressed_total 4541
telemt_desync_frames_bucket_total{bucket="1_2"} 1905
telemt_desync_frames_bucket_total{bucket="3_10"} 2371
telemt_desync_frames_bucket_total{bucket="gt_10"} 2046
telemt_pool_swap_total 47
telemt_pool_force_close_total 1298
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 148
telemt_me_draining_writers_reap_progress_total 15254
telemt_me_writer_removed_unexpected_total 255
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1056
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14404
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1271
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 27
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13956
telemt_me_writer_teardown_success_total{mode="normal"} 15460
telemt_me_writer_teardown_noop_total 15256
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 28129
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 28776
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 29255
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 29984
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 30493
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 30688
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 30716
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 30716
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 30716
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 30716
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 30716
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 30716
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 30716
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 52.928306
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 30716
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 148
telemt_me_refill_failed_total 12
telemt_me_writer_restored_same_endpoint_total 238
telemt_me_writer_removed_unexpected_minus_restored_total 17
telemt_user_connections_total{user="hello"} 853243
telemt_user_connections_current{user="hello"} 1548
telemt_user_octets_from_client{user="hello"} 12378879052 (11.53 GB)
telemt_user_octets_to_client{user="hello"} 274271268052 (255.44 GB)
telemt_user_unique_ips_current{user="hello"} 594
telemt_user_unique_ips_recent_window{user="hello"} 240
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 55824.5 (15h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1546827
telemt_connections_bad_total 152732
telemt_connections_current 1666
telemt_connections_me_current 1666
telemt_handshake_timeouts_total 43227
telemt_upstream_connect_attempt_total 29007
telemt_upstream_connect_success_total 28581
telemt_upstream_connect_fail_total 374
telemt_upstream_connect_attempts_per_request{bucket="1"} 28955
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14353
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14166
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 374
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 2481
telemt_me_reconnect_success_total 1062
telemt_me_reader_eof_total 965
telemt_me_idle_close_by_peer_total 965
telemt_me_route_drop_no_conn_total 729943
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1169590
telemt_me_endpoint_quarantine_total 485
telemt_me_single_endpoint_outage_enter_total 24
telemt_me_single_endpoint_outage_exit_total 24
telemt_me_single_endpoint_outage_reconnect_attempt_total 24
telemt_me_single_endpoint_outage_reconnect_success_total 24
telemt_me_single_endpoint_quarantine_bypass_total 24
telemt_me_single_endpoint_shadow_rotate_total 441
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 27
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
telemt_me_writers_active_current 42
telemt_desync_total 5200
telemt_desync_full_logged_total 3002
telemt_desync_suppressed_total 2198
telemt_desync_frames_bucket_total{bucket="1_2"} 1138
telemt_desync_frames_bucket_total{bucket="3_10"} 2017
telemt_desync_frames_bucket_total{bucket="gt_10"} 2045
telemt_pool_swap_total 57
telemt_pool_force_close_total 1581
telemt_me_writer_close_signal_drop_total 130
telemt_me_draining_writers_reap_progress_total 22725
telemt_me_writer_removed_unexpected_total 935
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2222
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21427
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1457
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 124
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21144
telemt_me_writer_teardown_success_total{mode="normal"} 23649
telemt_me_writer_teardown_noop_total 22725
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 45462
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 46015
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 46208
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 46360
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 46372
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 46374
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 46374
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 46374
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 46374
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 46374
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 46374
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 46374
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 46374
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 6.111145
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 46374
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 130
telemt_me_refill_failed_total 68
telemt_me_writer_restored_same_endpoint_total 860
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 19
telemt_me_writer_removed_unexpected_minus_restored_total 56
telemt_user_connections_total{user="hello"} 1171137
telemt_user_connections_current{user="hello"} 1666
telemt_user_octets_from_client{user="hello"} 17887630526 (16.66 GB)
telemt_user_octets_to_client{user="hello"} 397573297771 (370.27 GB)
telemt_user_msgs_from_client{user="hello"} 6406
telemt_user_msgs_to_client{user="hello"} 10605
telemt_user_unique_ips_current{user="hello"} 1061
telemt_user_unique_ips_recent_window{user="hello"} 461
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 130684.5 (36h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9891795
telemt_connections_bad_total 881052
telemt_connections_current 5041
telemt_connections_me_current 5041
telemt_handshake_timeouts_total 294046
telemt_upstream_connect_attempt_total 48165
telemt_upstream_connect_success_total 48085
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 48093
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21729
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26155
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 195
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1944
telemt_me_reconnect_success_total 994
telemt_me_reader_eof_total 1003
telemt_me_idle_close_by_peer_total 1002
telemt_me_route_drop_no_conn_total 5649104
telemt_me_route_drop_channel_closed_total 82
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7774547
telemt_me_endpoint_quarantine_total 819
telemt_me_single_endpoint_outage_enter_total 6
telemt_me_single_endpoint_outage_exit_total 6
telemt_me_single_endpoint_outage_reconnect_attempt_total 6
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 6
telemt_me_single_endpoint_shadow_rotate_total 977
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 33
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
telemt_desync_total 33746
telemt_desync_full_logged_total 11061
telemt_desync_suppressed_total 22685
telemt_desync_frames_bucket_total{bucket="1_2"} 7428
telemt_desync_frames_bucket_total{bucket="3_10"} 13146
telemt_desync_frames_bucket_total{bucket="gt_10"} 13172
telemt_pool_swap_total 141
telemt_pool_force_close_total 4682
telemt_pool_stale_pick_total 18
telemt_me_writer_close_signal_drop_total 713
telemt_me_draining_writers_reap_progress_total 43940
telemt_me_writer_removed_unexpected_total 964
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3695
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 40665
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4367
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 315
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 39258
telemt_me_writer_teardown_success_total{mode="normal"} 44360
telemt_me_writer_teardown_noop_total 43984
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 80898
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 83184
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 84375
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 86128
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 87347
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 87993
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 88332
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 88344
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 88344
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 88344
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 88344
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 88344
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 88344
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 188.146854
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 88344
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 713
telemt_me_refill_failed_total 50
telemt_me_writer_restored_same_endpoint_total 890
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 69
telemt_user_connections_total{user="hello"} 7764665
telemt_user_connections_current{user="hello"} 5041
telemt_user_octets_from_client{user="hello"} 127580316248 (118.82 GB)
telemt_user_octets_to_client{user="hello"} 2570994345980 (2.34 TB)
telemt_user_unique_ips_current{user="hello"} 2071
telemt_user_unique_ips_recent_window{user="hello"} 717
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 130686.1 (36h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8054317
telemt_connections_bad_total 722947
telemt_connections_current 4255
telemt_connections_me_current 4255
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 257951
telemt_upstream_connect_attempt_total 54166
telemt_upstream_connect_success_total 53688
telemt_upstream_connect_fail_total 246
telemt_upstream_connect_attempts_per_request{bucket="1"} 53934
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26182
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26272
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 108
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1126
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 246
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 2923
telemt_me_reconnect_success_total 1097
telemt_me_reader_eof_total 1016
telemt_me_idle_close_by_peer_total 1016
telemt_me_route_drop_no_conn_total 2692421
telemt_me_route_drop_channel_closed_total 321
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5950589
telemt_me_endpoint_quarantine_total 831
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 23
telemt_me_single_endpoint_outage_reconnect_success_total 18
telemt_me_single_endpoint_quarantine_bypass_total 23
telemt_me_single_endpoint_shadow_rotate_total 1009
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 38
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
telemt_desync_total 27343
telemt_desync_full_logged_total 9312
telemt_desync_suppressed_total 18031
telemt_desync_frames_bucket_total{bucket="1_2"} 6602
telemt_desync_frames_bucket_total{bucket="3_10"} 10578
telemt_desync_frames_bucket_total{bucket="gt_10"} 10163
telemt_pool_swap_total 143
telemt_pool_force_close_total 4270
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 459
telemt_me_draining_writers_reap_progress_total 42141
telemt_me_writer_removed_unexpected_total 1035
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3599
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 39469
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4016
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 254
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 37871
telemt_me_writer_teardown_success_total{mode="normal"} 43068
telemt_me_writer_teardown_noop_total 42147
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 80956
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 82977
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 83732
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 84467
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 84977
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 85195
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 85215
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 85215
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 85215
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 85215
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 85215
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 85215
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 85215
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 59.030341
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 85215
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 459
telemt_me_refill_failed_total 101
telemt_me_writer_restored_same_endpoint_total 925
telemt_me_writer_restored_fallback_total 12
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 206
telemt_me_writer_removed_unexpected_minus_restored_total 98
telemt_user_connections_total{user="hello"} 5873124
telemt_user_connections_current{user="hello"} 4255
telemt_user_octets_from_client{user="hello"} 162263515591 (151.12 GB)
telemt_user_octets_to_client{user="hello"} 2821663882938 (2.57 TB)
telemt_user_msgs_from_client{user="hello"} 42822
telemt_user_msgs_to_client{user="hello"} 51589
telemt_user_unique_ips_current{user="hello"} 1741
telemt_user_unique_ips_recent_window{user="hello"} 615
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 130649.8 (36h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7730182
telemt_connections_bad_total 641177
telemt_connections_current 3821
telemt_connections_me_current 3821
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 256623
telemt_upstream_connect_attempt_total 58559
telemt_upstream_connect_success_total 57878
telemt_upstream_connect_fail_total 147
telemt_upstream_connect_attempts_per_request{bucket="1"} 58025
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28400
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27221
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 940
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1317
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 147
telemt_me_keepalive_timeout_total 237
telemt_me_reconnect_attempts_total 2863
telemt_me_reconnect_success_total 1241
telemt_me_reader_eof_total 1140
telemt_me_idle_close_by_peer_total 1140
telemt_me_route_drop_no_conn_total 3112708
telemt_me_route_drop_channel_closed_total 193
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5766528
telemt_me_endpoint_quarantine_total 914
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 18
telemt_me_single_endpoint_outage_reconnect_success_total 15
telemt_me_single_endpoint_quarantine_bypass_total 18
telemt_me_single_endpoint_shadow_rotate_total 960
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 50
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
telemt_me_writers_active_current 61
telemt_me_writers_warm_current 22
telemt_desync_total 27052
telemt_desync_full_logged_total 9213
telemt_desync_suppressed_total 17839
telemt_desync_frames_bucket_total{bucket="1_2"} 6530
telemt_desync_frames_bucket_total{bucket="3_10"} 10379
telemt_desync_frames_bucket_total{bucket="gt_10"} 10143
telemt_pool_swap_total 139
telemt_pool_force_close_total 4146
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 483
telemt_me_draining_writers_reap_progress_total 43066
telemt_me_writer_removed_unexpected_total 1152
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3847
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 40355
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3833
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 313
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 38920
telemt_me_writer_teardown_success_total{mode="normal"} 44202
telemt_me_writer_teardown_noop_total 43078
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 83694
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 85483
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 86113
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 86791
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 87126
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 87228
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 87278
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 87278
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 87280
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 87280
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 87280
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 87280
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 87280
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 46.897963
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 87280
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 483
telemt_me_refill_failed_total 88
telemt_me_writer_restored_same_endpoint_total 1078
telemt_me_writer_restored_fallback_total 6
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 68
telemt_user_connections_total{user="hello"} 5759551
telemt_user_connections_current{user="hello"} 3821
telemt_user_octets_from_client{user="hello"} 148775786023 (138.56 GB)
telemt_user_octets_to_client{user="hello"} 2553295478939 (2.32 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 1567
telemt_user_unique_ips_recent_window{user="hello"} 532
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 929.9 (0h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 343848
telemt_connections_bad_total 32793
telemt_connections_current 5843
telemt_connections_me_current 5843
telemt_handshake_timeouts_total 3656
telemt_upstream_connect_attempt_total 291
telemt_upstream_connect_success_total 269
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 282
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 131
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 126
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_timeout_total 29
telemt_me_reconnect_attempts_total 4
telemt_me_reconnect_success_total 8
telemt_me_reader_eof_total 3
telemt_me_idle_close_by_peer_total 3
telemt_me_route_drop_no_conn_total 618501
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 278932
telemt_me_endpoint_quarantine_total 2
telemt_me_single_endpoint_shadow_rotate_total 8
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 1
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
telemt_me_writers_active_current 49
telemt_me_writers_warm_current 6
telemt_desync_total 513
telemt_desync_full_logged_total 122
telemt_desync_suppressed_total 391
telemt_desync_frames_bucket_total{bucket="1_2"} 116
telemt_desync_frames_bucket_total{bucket="3_10"} 188
telemt_desync_frames_bucket_total{bucket="gt_10"} 209
telemt_pool_force_close_total 2
telemt_me_draining_writers_reap_progress_total 152
telemt_me_writer_removed_unexpected_total 3
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 149
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 150
telemt_me_writer_teardown_success_total{mode="normal"} 155
telemt_me_writer_teardown_noop_total 152
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 305
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 307
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 307
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 307
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 307
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 307
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 307
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 307
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 307
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 307
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 307
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 307
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.040183
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 307
telemt_me_writer_restored_same_endpoint_total 3
telemt_user_connections_total{user="hello"} 278924
telemt_user_connections_current{user="hello"} 5843
telemt_user_octets_from_client{user="hello"} 1710535408 (1.59 GB)
telemt_user_octets_to_client{user="hello"} 10383296332 (9.67 GB)
telemt_user_unique_ips_current{user="hello"} 2170
telemt_user_unique_ips_recent_window{user="hello"} 1141
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 130656.7 (36h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7369767
telemt_connections_bad_total 664609
telemt_connections_current 3437
telemt_connections_me_current 3437
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 151127
telemt_upstream_connect_attempt_total 74858
telemt_upstream_connect_success_total 74046
telemt_upstream_connect_fail_total 693
telemt_upstream_connect_attempts_per_request{bucket="1"} 74739
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 45277
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28327
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 441
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 693
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 70377
telemt_me_reconnect_success_total 2024
telemt_me_reader_eof_total 1771
telemt_me_idle_close_by_peer_total 1770
telemt_me_route_drop_no_conn_total 2889929
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 40
telemt_me_route_drop_queue_full_profile_total{profile="high"} 40
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5785450
telemt_me_endpoint_quarantine_total 884
telemt_me_single_endpoint_outage_enter_total 26
telemt_me_single_endpoint_outage_exit_total 26
telemt_me_single_endpoint_outage_reconnect_attempt_total 27
telemt_me_single_endpoint_outage_reconnect_success_total 26
telemt_me_single_endpoint_quarantine_bypass_total 27
telemt_me_single_endpoint_shadow_rotate_total 987
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 38
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
telemt_desync_total 29223
telemt_desync_full_logged_total 10161
telemt_desync_suppressed_total 19062
telemt_desync_frames_bucket_total{bucket="1_2"} 5834
telemt_desync_frames_bucket_total{bucket="3_10"} 11248
telemt_desync_frames_bucket_total{bucket="gt_10"} 12141
telemt_pool_swap_total 137
telemt_pool_force_close_total 3904
telemt_pool_stale_pick_total 66
telemt_me_writer_close_signal_drop_total 464
telemt_me_draining_writers_reap_progress_total 45301
telemt_me_writer_removed_unexpected_total 1801
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4587
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 42541
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3462
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 442
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 41397
telemt_me_writer_teardown_success_total{mode="normal"} 47128
telemt_me_writer_teardown_noop_total 45302
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 90896
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 91875
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 92174
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 92396
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 92427
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 92430
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 92430
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 92430
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 92430
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 92430
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 92430
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 92430
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 92430
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.370041
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 92430
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 464
telemt_me_refill_failed_total 4229
telemt_me_writer_restored_same_endpoint_total 1675
telemt_me_writer_restored_fallback_total 40
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7333
telemt_me_writer_removed_unexpected_minus_restored_total 86
telemt_user_connections_total{user="hello"} 5783627
telemt_user_connections_current{user="hello"} 3437
telemt_user_octets_from_client{user="hello"} 146599190675 (136.53 GB)
telemt_user_octets_to_client{user="hello"} 2388873185363 (2.17 TB)
telemt_user_msgs_from_client{user="hello"} 115484
telemt_user_msgs_to_client{user="hello"} 517108
telemt_user_unique_ips_current{user="hello"} 1389
telemt_user_unique_ips_recent_window{user="hello"} 970
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 67492.6 (18h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5851107
telemt_connections_bad_total 231176
telemt_connections_current 4743
telemt_connections_me_current 4743
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 2324774
telemt_upstream_connect_attempt_total 36095
telemt_upstream_connect_success_total 35841
telemt_upstream_connect_fail_total 247
telemt_upstream_connect_attempts_per_request{bucket="1"} 36088
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21247
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14504
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 247
telemt_me_reconnect_attempts_total 47376
telemt_me_reconnect_success_total 1184
telemt_me_reader_eof_total 854
telemt_me_idle_close_by_peer_total 854
telemt_me_route_drop_no_conn_total 1473044
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2935211
telemt_me_endpoint_quarantine_total 462
telemt_me_single_endpoint_outage_enter_total 13
telemt_me_single_endpoint_outage_exit_total 13
telemt_me_single_endpoint_outage_reconnect_attempt_total 52
telemt_me_single_endpoint_outage_reconnect_success_total 13
telemt_me_single_endpoint_quarantine_bypass_total 52
telemt_me_single_endpoint_shadow_rotate_total 514
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
telemt_me_writers_active_current 46
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 15953
telemt_desync_full_logged_total 5412
telemt_desync_suppressed_total 10541
telemt_desync_frames_bucket_total{bucket="1_2"} 3143
telemt_desync_frames_bucket_total{bucket="3_10"} 6138
telemt_desync_frames_bucket_total{bucket="gt_10"} 6672
telemt_pool_swap_total 72
telemt_pool_force_close_total 2160
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 203
telemt_me_draining_writers_reap_progress_total 24214
telemt_me_writer_removed_unexpected_total 924
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2081
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 23079
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1882
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 278
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22054
telemt_me_writer_teardown_success_total{mode="normal"} 25160
telemt_me_writer_teardown_noop_total 24220
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 48665
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 49065
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 49247
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 49380
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 49380
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 49380
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 49380
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 49380
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 49380
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 49380
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 49380
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 49380
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 49380
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.614541
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 49380
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 203
telemt_me_refill_failed_total 2687
telemt_me_writer_restored_same_endpoint_total 1056
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4328
telemt_user_connections_total{user="hello"} 2936175
telemt_user_connections_current{user="hello"} 4743
telemt_user_octets_from_client{user="hello"} 74612378660 (69.49 GB)
telemt_user_octets_to_client{user="hello"} 1279719305046 (1.16 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 1931
telemt_user_unique_ips_recent_window{user="hello"} 903
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 48463.7 (13h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 432772
telemt_connections_bad_total 2918
telemt_connections_current 930
telemt_connections_me_current 930
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 8557
telemt_upstream_connect_attempt_total 25823
telemt_upstream_connect_success_total 25763
telemt_upstream_connect_fail_total 55
telemt_upstream_connect_attempts_per_request{bucket="1"} 25818
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12104
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13405
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 254
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 55
telemt_me_reconnect_attempts_total 1015
telemt_me_reconnect_success_total 389
telemt_me_reader_eof_total 384
telemt_me_idle_close_by_peer_total 384
telemt_me_route_drop_no_conn_total 138164
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 390701
telemt_me_endpoint_quarantine_total 459
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 415
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 8
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
telemt_desync_total 1796
telemt_desync_full_logged_total 525
telemt_desync_suppressed_total 1271
telemt_desync_frames_bucket_total{bucket="1_2"} 519
telemt_desync_frames_bucket_total{bucket="3_10"} 706
telemt_desync_frames_bucket_total{bucket="gt_10"} 571
telemt_pool_swap_total 52
telemt_pool_force_close_total 1194
telemt_me_writer_close_signal_drop_total 46
telemt_me_draining_writers_reap_progress_total 20778
telemt_me_writer_removed_unexpected_total 368
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1463
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19699
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1166
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 28
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19584
telemt_me_writer_teardown_success_total{mode="normal"} 21162
telemt_me_writer_teardown_noop_total 20778
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 41599
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 41869
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 41930
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 41940
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 41940
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 41940
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 41940
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 41940
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 41940
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 41940
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 41940
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 41940
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 41940
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.864630
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 41940
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 46
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 338
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 28
telemt_user_connections_total{user="hello"} 392840
telemt_user_connections_current{user="hello"} 930
telemt_user_octets_from_client{user="hello"} 7731342401 (7.20 GB)
telemt_user_octets_to_client{user="hello"} 200266638631 (186.51 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 341
telemt_user_unique_ips_recent_window{user="hello"} 146
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 130661.0 (36h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9076013
telemt_connections_bad_total 1052800
telemt_connections_current 4646
telemt_connections_me_current 4646
telemt_handshake_timeouts_total 250674
telemt_upstream_connect_attempt_total 50761
telemt_upstream_connect_success_total 50567
telemt_upstream_connect_fail_total 150
telemt_upstream_connect_attempts_per_request{bucket="1"} 50717
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25029
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25497
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 150
telemt_me_reconnect_attempts_total 1903
telemt_me_reconnect_success_total 1035
telemt_me_reader_eof_total 1006
telemt_me_idle_close_by_peer_total 1006
telemt_me_route_drop_no_conn_total 2545252
telemt_me_route_drop_channel_closed_total 64
telemt_me_route_drop_queue_full_total 25
telemt_me_route_drop_queue_full_profile_total{profile="high"} 25
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6718451
telemt_me_endpoint_quarantine_total 930
telemt_me_single_endpoint_outage_enter_total 10
telemt_me_single_endpoint_outage_exit_total 10
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 993
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 36
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
telemt_desync_total 27014
telemt_desync_full_logged_total 8856
telemt_desync_suppressed_total 18158
telemt_desync_frames_bucket_total{bucket="1_2"} 6697
telemt_desync_frames_bucket_total{bucket="3_10"} 9840
telemt_desync_frames_bucket_total{bucket="gt_10"} 10477
telemt_pool_swap_total 145
telemt_pool_force_close_total 3872
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 472
telemt_me_draining_writers_reap_progress_total 45769
telemt_me_writer_removed_unexpected_total 967
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3656
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 43110
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3770
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 102
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 41897
telemt_me_writer_teardown_success_total{mode="normal"} 46766
telemt_me_writer_teardown_noop_total 45771
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 90907
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 92007
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 92212
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 92437
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 92534
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 92537
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 92537
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 92537
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 92537
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 92537
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 92537
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 92537
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 92537
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 12.612048
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 92537
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 472
telemt_me_refill_failed_total 45
telemt_me_writer_restored_same_endpoint_total 907
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 24
telemt_me_writer_removed_unexpected_minus_restored_total 51
telemt_user_connections_total{user="hello"} 6691442
telemt_user_connections_current{user="hello"} 4646
telemt_user_octets_from_client{user="hello"} 130448974820 (121.49 GB)
telemt_user_octets_to_client{user="hello"} 3147726026968 (2.86 TB)
telemt_user_unique_ips_current{user="hello"} 1867
telemt_user_unique_ips_recent_window{user="hello"} 629
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 130658.0 (36h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7877187
telemt_connections_bad_total 879758
telemt_connections_current 4248
telemt_connections_me_current 4248
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 208835
telemt_upstream_connect_attempt_total 66801
telemt_upstream_connect_success_total 66282
telemt_upstream_connect_fail_total 452
telemt_upstream_connect_attempts_per_request{bucket="1"} 66734
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37949
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27184
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 631
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 452
telemt_me_reconnect_attempts_total 6399
telemt_me_reconnect_success_total 1467
telemt_me_reader_eof_total 1316
telemt_me_idle_close_by_peer_total 1316
telemt_me_seq_mismatch_total 62
telemt_me_route_drop_no_conn_total 2685398
telemt_me_route_drop_channel_closed_total 233
telemt_me_route_drop_queue_full_total 14
telemt_me_route_drop_queue_full_profile_total{profile="high"} 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5993841
telemt_me_endpoint_quarantine_total 1023
telemt_me_single_endpoint_outage_enter_total 33
telemt_me_single_endpoint_outage_exit_total 33
telemt_me_single_endpoint_outage_reconnect_attempt_total 33
telemt_me_single_endpoint_outage_reconnect_success_total 31
telemt_me_single_endpoint_quarantine_bypass_total 33
telemt_me_single_endpoint_shadow_rotate_total 990
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
telemt_desync_total 25893
telemt_desync_full_logged_total 8610
telemt_desync_suppressed_total 17283
telemt_desync_frames_bucket_total{bucket="1_2"} 6383
telemt_desync_frames_bucket_total{bucket="3_10"} 9508
telemt_desync_frames_bucket_total{bucket="gt_10"} 10002
telemt_pool_swap_total 142
telemt_pool_force_close_total 3820
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 466
telemt_me_draining_writers_reap_progress_total 44402
telemt_me_writer_removed_unexpected_total 1332
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4260
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 41536
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3547
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 273
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 40582
telemt_me_writer_teardown_success_total{mode="normal"} 45796
telemt_me_writer_teardown_noop_total 44406
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 88258
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 89483
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 89934
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 90164
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 90202
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 90202
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 90202
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 90202
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 90202
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 90202
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 90202
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 90202
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 90202
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 12.899954
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 90202
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 466
telemt_me_refill_failed_total 285
telemt_me_writer_restored_same_endpoint_total 1148
telemt_me_writer_restored_fallback_total 86
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 112
telemt_me_writer_removed_unexpected_minus_restored_total 98
telemt_user_connections_total{user="hello"} 5994592
telemt_user_connections_current{user="hello"} 4248
telemt_user_octets_from_client{user="hello"} 110116511125 (102.55 GB)
telemt_user_octets_to_client{user="hello"} 2586388833136 (2.35 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1741
telemt_user_unique_ips_recent_window{user="hello"} 613
```