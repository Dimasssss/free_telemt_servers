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

# Server Metrics 2026-03-22 06:20:45 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 33262.5 (9h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 630069
telemt_connections_bad_total 39259
telemt_connections_current 1383
telemt_connections_me_current 1383
telemt_handshake_timeouts_total 31166
telemt_upstream_connect_attempt_total 13598
telemt_upstream_connect_success_total 13597
telemt_upstream_connect_attempts_per_request{bucket="1"} 13597
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4733
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8824
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 29
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_reconnect_attempts_total 363
telemt_me_reconnect_success_total 212
telemt_me_reader_eof_total 208
telemt_me_idle_close_by_peer_total 208
telemt_me_route_drop_no_conn_total 229577
telemt_me_route_drop_channel_closed_total 71
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 522187
telemt_me_endpoint_quarantine_total 245
telemt_me_single_endpoint_shadow_rotate_total 274
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 7
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
telemt_me_writers_active_current 45
telemt_desync_total 4416
telemt_desync_full_logged_total 1225
telemt_desync_suppressed_total 3191
telemt_desync_frames_bucket_total{bucket="1_2"} 1463
telemt_desync_frames_bucket_total{bucket="3_10"} 1659
telemt_desync_frames_bucket_total{bucket="gt_10"} 1294
telemt_pool_swap_total 36
telemt_pool_force_close_total 961
telemt_me_writer_close_signal_drop_total 104
telemt_me_draining_writers_reap_progress_total 12308
telemt_me_writer_removed_unexpected_total 205
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 845
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 11655
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 951
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 11347
telemt_me_writer_teardown_success_total{mode="normal"} 12500
telemt_me_writer_teardown_noop_total 12309
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 23370
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 23849
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 24116
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 24479
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 24708
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 24800
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 24809
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 24809
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 24809
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 24809
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 24809
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 24809
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 24809
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 25.251625
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 24809
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 104
telemt_me_refill_failed_total 8
telemt_me_writer_restored_same_endpoint_total 193
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 521096
telemt_user_connections_current{user="hello"} 1383
telemt_user_octets_from_client{user="hello"} 7030096016 (6.55 GB)
telemt_user_octets_to_client{user="hello"} 181118509960 (168.68 GB)
telemt_user_unique_ips_current{user="hello"} 556
telemt_user_unique_ips_recent_window{user="hello"} 206
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 46629.4 (12h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1086900
telemt_connections_bad_total 99579
telemt_connections_current 1734
telemt_connections_me_current 1734
telemt_handshake_timeouts_total 35845
telemt_upstream_connect_attempt_total 24685
telemt_upstream_connect_success_total 24347
telemt_upstream_connect_fail_total 306
telemt_upstream_connect_attempts_per_request{bucket="1"} 24653
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12366
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11927
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 306
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 1860
telemt_me_reconnect_success_total 705
telemt_me_reader_eof_total 628
telemt_me_idle_close_by_peer_total 628
telemt_me_route_drop_no_conn_total 403978
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 830293
telemt_me_endpoint_quarantine_total 420
telemt_me_single_endpoint_outage_enter_total 21
telemt_me_single_endpoint_outage_exit_total 21
telemt_me_single_endpoint_outage_reconnect_attempt_total 21
telemt_me_single_endpoint_outage_reconnect_success_total 21
telemt_me_single_endpoint_quarantine_bypass_total 21
telemt_me_single_endpoint_shadow_rotate_total 376
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 23
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
telemt_desync_total 3497
telemt_desync_full_logged_total 2039
telemt_desync_suppressed_total 1458
telemt_desync_frames_bucket_total{bucket="1_2"} 740
telemt_desync_frames_bucket_total{bucket="3_10"} 1345
telemt_desync_frames_bucket_total{bucket="gt_10"} 1412
telemt_pool_swap_total 49
telemt_pool_force_close_total 1287
telemt_me_writer_close_signal_drop_total 98
telemt_me_draining_writers_reap_progress_total 19210
telemt_me_writer_removed_unexpected_total 602
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1670
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18156
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1265
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 22
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17923
telemt_me_writer_teardown_success_total{mode="normal"} 19826
telemt_me_writer_teardown_noop_total 19210
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 38417
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 38778
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 38906
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 39022
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 39034
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 39036
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 39036
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 39036
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 39036
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 39036
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 39036
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 39036
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 39036
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.449344
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 39036
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 98
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 543
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 831958
telemt_user_connections_current{user="hello"} 1734
telemt_user_octets_from_client{user="hello"} 13589327011 (12.66 GB)
telemt_user_octets_to_client{user="hello"} 308676723366 (287.48 GB)
telemt_user_msgs_from_client{user="hello"} 6021
telemt_user_msgs_to_client{user="hello"} 9976
telemt_user_unique_ips_current{user="hello"} 1048
telemt_user_unique_ips_recent_window{user="hello"} 383
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 121489.2 (33h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8559182
telemt_connections_bad_total 764336
telemt_connections_current 4122
telemt_connections_me_current 4122
telemt_handshake_timeouts_total 275110
telemt_upstream_connect_attempt_total 45060
telemt_upstream_connect_success_total 44982
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 44990
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20338
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24452
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 186
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1715
telemt_me_reconnect_success_total 879
telemt_me_reader_eof_total 892
telemt_me_idle_close_by_peer_total 892
telemt_me_route_drop_no_conn_total 4730368
telemt_me_route_drop_channel_closed_total 71
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6818464
telemt_me_endpoint_quarantine_total 769
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 912
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
telemt_me_writers_active_current 43
telemt_desync_total 29132
telemt_desync_full_logged_total 9673
telemt_desync_suppressed_total 19459
telemt_desync_frames_bucket_total{bucket="1_2"} 6305
telemt_desync_frames_bucket_total{bucket="3_10"} 11383
telemt_desync_frames_bucket_total{bucket="gt_10"} 11444
telemt_pool_swap_total 131
telemt_pool_force_close_total 4324
telemt_pool_stale_pick_total 18
telemt_me_writer_close_signal_drop_total 650
telemt_me_draining_writers_reap_progress_total 41137
telemt_me_writer_removed_unexpected_total 858
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3403
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 38098
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4073
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 251
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 36813
telemt_me_writer_teardown_success_total{mode="normal"} 41501
telemt_me_writer_teardown_noop_total 41181
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 75896
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 77916
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 79022
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 80637
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 81779
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 82377
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 82671
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 82682
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 82682
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 82682
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 82682
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 82682
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 82682
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 170.838633
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 82682
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 650
telemt_me_refill_failed_total 44
telemt_me_writer_restored_same_endpoint_total 786
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 67
telemt_user_connections_total{user="hello"} 6809643
telemt_user_connections_current{user="hello"} 4122
telemt_user_octets_from_client{user="hello"} 115642655624 (107.70 GB)
telemt_user_octets_to_client{user="hello"} 2324593286824 (2.11 TB)
telemt_user_unique_ips_current{user="hello"} 1710
telemt_user_unique_ips_recent_window{user="hello"} 568
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 121490.0 (33h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7063313
telemt_connections_bad_total 627649
telemt_connections_current 3644
telemt_connections_me_current 3644
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 235280
telemt_upstream_connect_attempt_total 49022
telemt_upstream_connect_success_total 48619
telemt_upstream_connect_fail_total 206
telemt_upstream_connect_attempts_per_request{bucket="1"} 48825
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23979
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24048
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 559
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 206
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 2064
telemt_me_reconnect_success_total 940
telemt_me_reader_eof_total 920
telemt_me_idle_close_by_peer_total 920
telemt_me_route_drop_no_conn_total 2398223
telemt_me_route_drop_channel_closed_total 293
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5252093
telemt_me_endpoint_quarantine_total 766
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 934
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 31
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
telemt_desync_total 24282
telemt_desync_full_logged_total 8342
telemt_desync_suppressed_total 15940
telemt_desync_frames_bucket_total{bucket="1_2"} 5810
telemt_desync_frames_bucket_total{bucket="3_10"} 9430
telemt_desync_frames_bucket_total{bucket="gt_10"} 9042
telemt_pool_swap_total 132
telemt_pool_force_close_total 3932
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 397
telemt_me_draining_writers_reap_progress_total 39572
telemt_me_writer_removed_unexpected_total 897
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3257
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 37141
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3710
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 222
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 35640
telemt_me_writer_teardown_success_total{mode="normal"} 40398
telemt_me_writer_teardown_noop_total 39578
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 76312
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 78038
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 78697
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 79332
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 79767
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 79956
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 79976
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 79976
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 79976
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 79976
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 79976
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 79976
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 79976
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 51.505172
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 79976
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 397
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 821
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 66
telemt_user_connections_total{user="hello"} 5173397
telemt_user_connections_current{user="hello"} 3644
telemt_user_octets_from_client{user="hello"} 148880240189 (138.66 GB)
telemt_user_octets_to_client{user="hello"} 2492360811487 (2.27 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1497
telemt_user_unique_ips_recent_window{user="hello"} 493
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 121454.1 (33h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6860936
telemt_connections_bad_total 574558
telemt_connections_current 2782
telemt_connections_me_current 2782
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 231122
telemt_upstream_connect_attempt_total 55474
telemt_upstream_connect_success_total 54880
telemt_upstream_connect_fail_total 144
telemt_upstream_connect_attempts_per_request{bucket="1"} 55024
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27271
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25587
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 803
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1219
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 144
telemt_me_keepalive_timeout_total 95
telemt_me_reconnect_attempts_total 2584
telemt_me_reconnect_success_total 1115
telemt_me_reader_eof_total 1038
telemt_me_idle_close_by_peer_total 1038
telemt_me_route_drop_no_conn_total 2477558
telemt_me_route_drop_channel_closed_total 155
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5100519
telemt_me_endpoint_quarantine_total 868
telemt_me_single_endpoint_outage_enter_total 17
telemt_me_single_endpoint_outage_exit_total 17
telemt_me_single_endpoint_outage_reconnect_attempt_total 17
telemt_me_single_endpoint_outage_reconnect_success_total 14
telemt_me_single_endpoint_quarantine_bypass_total 17
telemt_me_single_endpoint_shadow_rotate_total 900
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 47
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
telemt_desync_total 24195
telemt_desync_full_logged_total 8197
telemt_desync_suppressed_total 15998
telemt_desync_frames_bucket_total{bucket="1_2"} 5872
telemt_desync_frames_bucket_total{bucket="3_10"} 9305
telemt_desync_frames_bucket_total{bucket="gt_10"} 9018
telemt_pool_swap_total 130
telemt_pool_force_close_total 3796
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 426
telemt_me_draining_writers_reap_progress_total 40528
telemt_me_writer_removed_unexpected_total 1029
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3515
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 38059
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3548
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 248
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 36732
telemt_me_writer_teardown_success_total{mode="normal"} 41574
telemt_me_writer_teardown_noop_total 40540
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 79049
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 80612
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 81136
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 81721
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 82004
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 82070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 82114
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 82114
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 82114
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 82114
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 82114
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 82114
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 82114
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 38.121922
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 82114
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 426
telemt_me_refill_failed_total 80
telemt_me_writer_restored_same_endpoint_total 962
telemt_me_writer_restored_fallback_total 6
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 61
telemt_user_connections_total{user="hello"} 5094730
telemt_user_connections_current{user="hello"} 2782
telemt_user_octets_from_client{user="hello"} 139446136339 (129.87 GB)
telemt_user_octets_to_client{user="hello"} 2318141052163 (2.11 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 1202
telemt_user_unique_ips_recent_window{user="hello"} 406
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 121493.4 (33h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21910237
telemt_connections_bad_total 1855485
telemt_connections_current 4638
telemt_connections_me_current 4638
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 661971
telemt_upstream_connect_attempt_total 225141
telemt_upstream_connect_success_total 205990
telemt_upstream_connect_fail_total 17224
telemt_upstream_connect_attempts_per_request{bucket="1"} 223214
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 145255
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 48585
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1954
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10196
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17224
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 66328
telemt_me_reconnect_success_total 2586
telemt_me_reader_eof_total 1623
telemt_me_idle_close_by_peer_total 1622
telemt_me_route_drop_no_conn_total 41458627
telemt_me_route_drop_channel_closed_total 132
telemt_me_route_drop_queue_full_total 13
telemt_me_route_drop_queue_full_profile_total{profile="high"} 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 17610483
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 950
telemt_me_single_endpoint_outage_enter_total 155
telemt_me_single_endpoint_outage_exit_total 155
telemt_me_single_endpoint_outage_reconnect_attempt_total 324
telemt_me_single_endpoint_outage_reconnect_success_total 81
telemt_me_single_endpoint_quarantine_bypass_total 324
telemt_me_single_endpoint_shadow_rotate_total 953
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 70
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
telemt_desync_total 34072
telemt_desync_full_logged_total 10226
telemt_desync_suppressed_total 23846
telemt_desync_frames_bucket_total{bucket="1_2"} 7513
telemt_desync_frames_bucket_total{bucket="3_10"} 15093
telemt_desync_frames_bucket_total{bucket="gt_10"} 11466
telemt_pool_swap_total 125
telemt_pool_force_close_total 3979
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 903
telemt_me_draining_writers_reap_progress_total 38085
telemt_me_writer_removed_unexpected_total 2399
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5171
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 35062
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 24
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3416
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 563
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 34106
telemt_me_writer_teardown_success_total{mode="normal"} 40233
telemt_me_writer_teardown_noop_total 38112
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 71088
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 73786
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 75142
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 76892
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 77884
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 78232
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 78317
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 78321
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 78329
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 78336
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 78336
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 78340
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 78345
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 227.200976
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 78345
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 903
telemt_me_refill_failed_total 3862
telemt_me_writer_restored_same_endpoint_total 1757
telemt_me_writer_restored_fallback_total 22
telemt_me_no_writer_failfast_total 669
telemt_me_async_recovery_trigger_total 14705
telemt_me_writer_removed_unexpected_minus_restored_total 620
telemt_user_connections_total{user="hello"} 17763174
telemt_user_connections_current{user="hello"} 4638
telemt_user_octets_from_client{user="hello"} 263171194497 (245.10 GB)
telemt_user_octets_to_client{user="hello"} 1363660423479 (1.24 TB)
telemt_user_msgs_from_client{user="hello"} 454370
telemt_user_msgs_to_client{user="hello"} 903931
telemt_user_unique_ips_current{user="hello"} 1777
telemt_user_unique_ips_recent_window{user="hello"} 772
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 121461.0 (33h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6592786
telemt_connections_bad_total 617684
telemt_connections_current 3404
telemt_connections_me_current 3404
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 137447
telemt_upstream_connect_attempt_total 64111
telemt_upstream_connect_success_total 63372
telemt_upstream_connect_fail_total 633
telemt_upstream_connect_attempts_per_request{bucket="1"} 64005
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36409
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26600
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 362
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 633
telemt_me_reconnect_attempts_total 69969
telemt_me_reconnect_success_total 1907
telemt_me_reader_eof_total 1683
telemt_me_idle_close_by_peer_total 1682
telemt_me_route_drop_no_conn_total 2528372
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5144013
telemt_me_endpoint_quarantine_total 817
telemt_me_single_endpoint_outage_enter_total 24
telemt_me_single_endpoint_outage_exit_total 24
telemt_me_single_endpoint_outage_reconnect_attempt_total 25
telemt_me_single_endpoint_outage_reconnect_success_total 24
telemt_me_single_endpoint_quarantine_bypass_total 25
telemt_me_single_endpoint_shadow_rotate_total 921
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 34
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
telemt_desync_total 25617
telemt_desync_full_logged_total 8955
telemt_desync_suppressed_total 16662
telemt_desync_frames_bucket_total{bucket="1_2"} 5061
telemt_desync_frames_bucket_total{bucket="3_10"} 9850
telemt_desync_frames_bucket_total{bucket="gt_10"} 10706
telemt_pool_swap_total 126
telemt_pool_force_close_total 3608
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 426
telemt_me_draining_writers_reap_progress_total 42757
telemt_me_writer_removed_unexpected_total 1716
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4294
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 40214
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3202
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 406
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 39149
telemt_me_writer_teardown_success_total{mode="normal"} 44508
telemt_me_writer_teardown_noop_total 42758
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 85837
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 86743
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 87037
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 87232
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 87263
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 87266
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 87266
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 87266
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 87266
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 87266
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 87266
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 87266
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 87266
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 9.708248
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 87266
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 426
telemt_me_refill_failed_total 4216
telemt_me_writer_restored_same_endpoint_total 1593
telemt_me_writer_restored_fallback_total 38
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7313
telemt_me_writer_removed_unexpected_minus_restored_total 85
telemt_user_connections_total{user="hello"} 5135823
telemt_user_connections_current{user="hello"} 3404
telemt_user_octets_from_client{user="hello"} 131843596100 (122.79 GB)
telemt_user_octets_to_client{user="hello"} 2144417087778 (1.95 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 1408
telemt_user_unique_ips_recent_window{user="hello"} 489
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 58297.0 (16h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4685631
telemt_connections_bad_total 196770
telemt_connections_current 3007
telemt_connections_me_current 3007
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 1842900
telemt_upstream_connect_attempt_total 32904
telemt_upstream_connect_success_total 32684
telemt_upstream_connect_fail_total 213
telemt_upstream_connect_attempts_per_request{bucket="1"} 32897
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19742
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12858
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 84
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 213
telemt_me_reconnect_attempts_total 46173
telemt_me_reconnect_success_total 1051
telemt_me_reader_eof_total 742
telemt_me_idle_close_by_peer_total 742
telemt_me_route_drop_no_conn_total 1162734
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2331991
telemt_me_endpoint_quarantine_total 414
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 51
telemt_me_single_endpoint_outage_reconnect_success_total 12
telemt_me_single_endpoint_quarantine_bypass_total 51
telemt_me_single_endpoint_shadow_rotate_total 449
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
telemt_me_writers_active_current 43
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 12487
telemt_desync_full_logged_total 4304
telemt_desync_suppressed_total 8183
telemt_desync_frames_bucket_total{bucket="1_2"} 2405
telemt_desync_frames_bucket_total{bucket="3_10"} 4775
telemt_desync_frames_bucket_total{bucket="gt_10"} 5307
telemt_pool_swap_total 63
telemt_pool_force_close_total 1848
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 162
telemt_me_draining_writers_reap_progress_total 21425
telemt_me_writer_removed_unexpected_total 812
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1816
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20451
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1635
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 213
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19577
telemt_me_writer_teardown_success_total{mode="normal"} 22267
telemt_me_writer_teardown_noop_total 21427
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 43119
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 43429
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 43588
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 43694
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 43694
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 43694
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 43694
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 43694
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 43694
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 43694
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 43694
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 43694
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 43694
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.760639
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 43694
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 162
telemt_me_refill_failed_total 2621
telemt_me_writer_restored_same_endpoint_total 936
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4264
telemt_user_connections_total{user="hello"} 2334102
telemt_user_connections_current{user="hello"} 3007
telemt_user_octets_from_client{user="hello"} 61095349500 (56.90 GB)
telemt_user_octets_to_client{user="hello"} 1036235276326 (965.07 GB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 1314
telemt_user_unique_ips_recent_window{user="hello"} 475
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 39268.1 (10h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 288461
telemt_connections_bad_total 2033
telemt_connections_current 612
telemt_connections_me_current 612
telemt_handshake_timeouts_total 6966
telemt_upstream_connect_attempt_total 18886
telemt_upstream_connect_success_total 18840
telemt_upstream_connect_fail_total 42
telemt_upstream_connect_attempts_per_request{bucket="1"} 18882
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7913
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10824
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 103
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 42
telemt_me_reconnect_attempts_total 490
telemt_me_reconnect_success_total 260
telemt_me_reader_eof_total 261
telemt_me_idle_close_by_peer_total 261
telemt_me_route_drop_no_conn_total 83365
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 259329
telemt_me_endpoint_quarantine_total 370
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 340
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 6
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
telemt_desync_total 1299
telemt_desync_full_logged_total 364
telemt_desync_suppressed_total 935
telemt_desync_frames_bucket_total{bucket="1_2"} 443
telemt_desync_frames_bucket_total{bucket="3_10"} 499
telemt_desync_frames_bucket_total{bucket="gt_10"} 357
telemt_pool_swap_total 43
telemt_pool_force_close_total 962
telemt_me_writer_close_signal_drop_total 35
telemt_me_draining_writers_reap_progress_total 17098
telemt_me_writer_removed_unexpected_total 250
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1095
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16264
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 960
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16136
telemt_me_writer_teardown_success_total{mode="normal"} 17359
telemt_me_writer_teardown_noop_total 17098
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 34171
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 34429
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 34447
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 34457
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 34457
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 34457
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 34457
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 34457
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 34457
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 34457
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 34457
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 34457
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 34457
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.354198
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 34457
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 35
telemt_me_refill_failed_total 13
telemt_me_writer_restored_same_endpoint_total 226
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 258923
telemt_user_connections_current{user="hello"} 612
telemt_user_octets_from_client{user="hello"} 4344573204 (4.05 GB)
telemt_user_octets_to_client{user="hello"} 153493620804 (142.95 GB)
telemt_user_unique_ips_current{user="hello"} 254
telemt_user_unique_ips_recent_window{user="hello"} 96
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 121465.6 (33h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7997024
telemt_connections_bad_total 807690
telemt_connections_current 3647
telemt_connections_me_current 3647
telemt_handshake_timeouts_total 225974
telemt_upstream_connect_attempt_total 47766
telemt_upstream_connect_success_total 47593
telemt_upstream_connect_fail_total 136
telemt_upstream_connect_attempts_per_request{bucket="1"} 47729
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23561
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23991
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 136
telemt_me_reconnect_attempts_total 1762
telemt_me_reconnect_success_total 944
telemt_me_reader_eof_total 928
telemt_me_idle_close_by_peer_total 928
telemt_me_route_drop_no_conn_total 2262192
telemt_me_route_drop_channel_closed_total 54
telemt_me_route_drop_queue_full_total 23
telemt_me_route_drop_queue_full_profile_total{profile="high"} 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5968881
telemt_me_endpoint_quarantine_total 865
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 930
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
telemt_me_writers_active_current 46
telemt_desync_total 23479
telemt_desync_full_logged_total 7729
telemt_desync_suppressed_total 15750
telemt_desync_frames_bucket_total{bucket="1_2"} 5865
telemt_desync_frames_bucket_total{bucket="3_10"} 8565
telemt_desync_frames_bucket_total{bucket="gt_10"} 9049
telemt_pool_swap_total 134
telemt_pool_force_close_total 3572
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 422
telemt_me_draining_writers_reap_progress_total 43120
telemt_me_writer_removed_unexpected_total 891
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3376
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 40662
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3481
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 91
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 39548
telemt_me_writer_teardown_success_total{mode="normal"} 44038
telemt_me_writer_teardown_noop_total 43122
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 85706
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 86675
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 86862
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 87069
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 87160
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 87160
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 87160
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 87160
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 87160
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 87160
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 87160
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 87160
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 87160
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 11.207556
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 87160
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 422
telemt_me_refill_failed_total 43
telemt_me_writer_restored_same_endpoint_total 840
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 24
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 5943194
telemt_user_connections_current{user="hello"} 3647
telemt_user_octets_from_client{user="hello"} 116549217972 (108.54 GB)
telemt_user_octets_to_client{user="hello"} 2791459963636 (2.54 TB)
telemt_user_unique_ips_current{user="hello"} 1429
telemt_user_unique_ips_recent_window{user="hello"} 530
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 121461.9 (33h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6976160
telemt_connections_bad_total 698342
telemt_connections_current 3654
telemt_connections_me_current 3654
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 187360
telemt_upstream_connect_attempt_total 63547
telemt_upstream_connect_success_total 63061
telemt_upstream_connect_fail_total 423
telemt_upstream_connect_attempts_per_request{bucket="1"} 63484
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36309
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25618
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 616
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 423
telemt_me_reconnect_attempts_total 5860
telemt_me_reconnect_success_total 1309
telemt_me_reader_eof_total 1175
telemt_me_idle_close_by_peer_total 1175
telemt_me_seq_mismatch_total 58
telemt_me_route_drop_no_conn_total 2320987
telemt_me_route_drop_channel_closed_total 194
telemt_me_route_drop_queue_full_total 14
telemt_me_route_drop_queue_full_profile_total{profile="high"} 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5332759
telemt_me_endpoint_quarantine_total 956
telemt_me_single_endpoint_outage_enter_total 30
telemt_me_single_endpoint_outage_exit_total 30
telemt_me_single_endpoint_outage_reconnect_attempt_total 30
telemt_me_single_endpoint_outage_reconnect_success_total 28
telemt_me_single_endpoint_quarantine_bypass_total 30
telemt_me_single_endpoint_shadow_rotate_total 929
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 35
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
telemt_me_writers_active_current 47
telemt_desync_total 22369
telemt_desync_full_logged_total 7442
telemt_desync_suppressed_total 14927
telemt_desync_frames_bucket_total{bucket="1_2"} 5604
telemt_desync_frames_bucket_total{bucket="3_10"} 8173
telemt_desync_frames_bucket_total{bucket="gt_10"} 8592
telemt_pool_swap_total 132
telemt_pool_force_close_total 3519
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 423
telemt_me_draining_writers_reap_progress_total 41605
telemt_me_writer_removed_unexpected_total 1188
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3927
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 38926
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3294
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 225
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 38086
telemt_me_writer_teardown_success_total{mode="normal"} 42853
telemt_me_writer_teardown_noop_total 41609
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 82678
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 83801
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 84224
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 84424
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 84462
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 84462
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 84462
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 84462
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 84462
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 84462
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 84462
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 84462
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 84462
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 11.908019
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 84462
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 423
telemt_me_refill_failed_total 262
telemt_me_writer_restored_same_endpoint_total 1018
telemt_me_writer_restored_fallback_total 77
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 82
telemt_me_writer_removed_unexpected_minus_restored_total 93
telemt_user_connections_total{user="hello"} 5335096
telemt_user_connections_current{user="hello"} 3654
telemt_user_octets_from_client{user="hello"} 99586984249 (92.75 GB)
telemt_user_octets_to_client{user="hello"} 2318957176844 (2.11 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1486
telemt_user_unique_ips_recent_window{user="hello"} 491
```