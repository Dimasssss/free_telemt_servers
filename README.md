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

# Server Metrics 2026-03-22 17:30:39 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 73456.0 (20h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2652833
telemt_connections_bad_total 143942
telemt_connections_current 1570
telemt_connections_me_current 1570
telemt_handshake_timeouts_total 91402
telemt_upstream_connect_attempt_total 27058
telemt_upstream_connect_success_total 27057
telemt_upstream_connect_attempts_per_request{bucket="1"} 27057
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9402
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17571
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 61
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 150
telemt_me_reconnect_attempts_total 1094
telemt_me_reconnect_success_total 467
telemt_me_reader_eof_total 469
telemt_me_idle_close_by_peer_total 469
telemt_me_route_drop_no_conn_total 2201064
telemt_me_route_drop_channel_closed_total 899
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2264157
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_endpoint_quarantine_total 503
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 575
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
telemt_me_writers_active_current 44
telemt_desync_total 10501
telemt_desync_full_logged_total 3327
telemt_desync_suppressed_total 7174
telemt_desync_frames_bucket_total{bucket="1_2"} 2812
telemt_desync_frames_bucket_total{bucket="3_10"} 3911
telemt_desync_frames_bucket_total{bucket="gt_10"} 3778
telemt_pool_swap_total 81
telemt_pool_force_close_total 2515
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 510
telemt_me_draining_writers_reap_progress_total 24711
telemt_me_writer_removed_unexpected_total 455
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1813
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 23124
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2463
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 52
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22196
telemt_me_writer_teardown_success_total{mode="normal"} 24937
telemt_me_writer_teardown_noop_total 24721
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 39853
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 41680
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 43430
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 46450
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 48457
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 49374
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 49654
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 49658
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 49658
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 49658
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 49658
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 49658
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 49658
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 243.006506
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 49658
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 510
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 413
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 41
telemt_user_connections_total{user="hello"} 2260416
telemt_user_connections_current{user="hello"} 1570
telemt_user_octets_from_client{user="hello"} 33332683036 (31.04 GB)
telemt_user_octets_to_client{user="hello"} 596488485380 (555.52 GB)
telemt_user_unique_ips_current{user="hello"} 600
telemt_user_unique_ips_recent_window{user="hello"} 271
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 86822.0 (24h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3673997
telemt_connections_bad_total 332806
telemt_connections_current 770
telemt_connections_me_current 770
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 92382
telemt_upstream_connect_attempt_total 53801
telemt_upstream_connect_success_total 53130
telemt_upstream_connect_fail_total 591
telemt_upstream_connect_attempts_per_request{bucket="1"} 53721
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30580
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22377
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 173
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 591
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 6231
telemt_me_reconnect_success_total 2259
telemt_me_reader_eof_total 2188
telemt_me_idle_close_by_peer_total 2188
telemt_me_route_drop_no_conn_total 3553232
telemt_me_route_drop_channel_closed_total 36
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2914713
telemt_me_endpoint_quarantine_total 689
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 39
telemt_me_single_endpoint_outage_exit_total 39
telemt_me_single_endpoint_outage_reconnect_attempt_total 39
telemt_me_single_endpoint_outage_reconnect_success_total 38
telemt_me_single_endpoint_quarantine_bypass_total 39
telemt_me_single_endpoint_shadow_rotate_total 670
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
telemt_me_writers_active_current 43
telemt_desync_total 11467
telemt_desync_full_logged_total 6406
telemt_desync_suppressed_total 5061
telemt_desync_frames_bucket_total{bucket="1_2"} 2675
telemt_desync_frames_bucket_total{bucket="3_10"} 4497
telemt_desync_frames_bucket_total{bucket="gt_10"} 4295
telemt_pool_swap_total 82
telemt_pool_force_close_total 2461
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 209
telemt_me_draining_writers_reap_progress_total 34527
telemt_me_writer_removed_unexpected_total 2141
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4125
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 32551
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2101
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 360
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 32066
telemt_me_writer_teardown_success_total{mode="normal"} 36676
telemt_me_writer_teardown_noop_total 34527
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 69461
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 70553
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 70831
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 71137
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 71188
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 71201
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 71203
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 71203
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 71203
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 71203
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 71203
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 71203
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 71203
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 13.232765
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 71203
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 209
telemt_me_refill_failed_total 157
telemt_me_writer_restored_same_endpoint_total 1950
telemt_me_writer_restored_fallback_total 25
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 166
telemt_user_connections_total{user="hello"} 2925914
telemt_user_connections_current{user="hello"} 770
telemt_user_octets_from_client{user="hello"} 37233737639 (34.68 GB)
telemt_user_octets_to_client{user="hello"} 664619232722 (618.97 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 467
telemt_user_unique_ips_recent_window{user="hello"} 261
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 161682.0 (44h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15545228
telemt_connections_bad_total 1485986
telemt_connections_current 2382
telemt_connections_me_current 2382
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 380640
telemt_upstream_connect_attempt_total 72671
telemt_upstream_connect_success_total 72574
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 72591
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36403
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34486
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1678
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2703
telemt_me_reconnect_success_total 1391
telemt_me_reader_eof_total 1329
telemt_me_idle_close_by_peer_total 1327
telemt_me_route_drop_no_conn_total 13858901
telemt_me_route_drop_channel_closed_total 140
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12391501
telemt_me_endpoint_quarantine_total 1016
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1204
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 41
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
telemt_me_writers_active_current 43
telemt_desync_total 50681
telemt_desync_full_logged_total 15923
telemt_desync_suppressed_total 34758
telemt_desync_frames_bucket_total{bucket="1_2"} 11323
telemt_desync_frames_bucket_total{bucket="3_10"} 19779
telemt_desync_frames_bucket_total{bucket="gt_10"} 19579
telemt_pool_swap_total 174
telemt_pool_force_close_total 5908
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 955
telemt_me_draining_writers_reap_progress_total 53137
telemt_me_writer_removed_unexpected_total 1283
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4653
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 49058
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 42
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5446
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 462
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 47229
telemt_me_writer_teardown_success_total{mode="normal"} 53711
telemt_me_writer_teardown_noop_total 53187
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 96648
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 99936
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 101547
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 103726
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 105302
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 106301
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 106859
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 106889
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 106890
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 106894
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 106896
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 106898
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 106898
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 303.642777
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 106898
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 955
telemt_me_refill_failed_total 72
telemt_me_writer_restored_same_endpoint_total 1196
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 80
telemt_user_connections_total{user="hello"} 12392488
telemt_user_connections_current{user="hello"} 2381
telemt_user_octets_from_client{user="hello"} 178258462293 (166.02 GB)
telemt_user_octets_to_client{user="hello"} 3225032945475 (2.93 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 975
telemt_user_unique_ips_recent_window{user="hello"} 335
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 161683.3 (44h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11204993
telemt_connections_bad_total 1091640
telemt_connections_current 1709
telemt_connections_me_current 1709
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 336308
telemt_upstream_connect_attempt_total 84978
telemt_upstream_connect_success_total 83805
telemt_upstream_connect_fail_total 838
telemt_upstream_connect_attempts_per_request{bucket="1"} 84643
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 45590
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34359
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 158
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3698
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 838
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 182
telemt_me_reconnect_attempts_total 4036
telemt_me_reconnect_success_total 1666
telemt_me_reader_eof_total 1535
telemt_me_idle_close_by_peer_total 1535
telemt_me_route_drop_no_conn_total 4401359
telemt_me_route_drop_channel_closed_total 487
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8351310
telemt_me_endpoint_quarantine_total 1018
telemt_me_single_endpoint_outage_enter_total 27
telemt_me_single_endpoint_outage_exit_total 27
telemt_me_single_endpoint_outage_reconnect_attempt_total 32
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 32
telemt_me_single_endpoint_shadow_rotate_total 1223
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 45
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
telemt_me_writers_active_current 79
telemt_desync_total 37158
telemt_desync_full_logged_total 12500
telemt_desync_suppressed_total 24658
telemt_desync_frames_bucket_total{bucket="1_2"} 9139
telemt_desync_frames_bucket_total{bucket="3_10"} 14314
telemt_desync_frames_bucket_total{bucket="gt_10"} 13705
telemt_pool_swap_total 171
telemt_pool_force_close_total 5320
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 677
telemt_me_draining_writers_reap_progress_total 51451
telemt_me_writer_removed_unexpected_total 1575
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4772
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 48096
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4842
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 478
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 46131
telemt_me_writer_teardown_success_total{mode="normal"} 52868
telemt_me_writer_teardown_noop_total 51474
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 97998
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 100972
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 102063
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 103184
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 103926
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 104257
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 104332
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 104334
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 104340
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 104342
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 104342
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 104342
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 104342
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 100.942562
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 104342
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 677
telemt_me_refill_failed_total 128
telemt_me_writer_restored_same_endpoint_total 1427
telemt_me_writer_restored_fallback_total 15
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 133
telemt_user_connections_total{user="hello"} 8289887
telemt_user_connections_current{user="hello"} 1709
telemt_user_octets_from_client{user="hello"} 207205573189 (192.98 GB)
telemt_user_octets_to_client{user="hello"} 3737605076562 (3.40 TB)
telemt_user_msgs_from_client{user="hello"} 113340
telemt_user_msgs_to_client{user="hello"} 116189
telemt_user_unique_ips_current{user="hello"} 644
telemt_user_unique_ips_recent_window{user="hello"} 247
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 161647.4 (44h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10568710
telemt_connections_bad_total 911545
telemt_connections_current 1393
telemt_connections_me_current 1393
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 338287
telemt_upstream_connect_attempt_total 70205
telemt_upstream_connect_success_total 69214
telemt_upstream_connect_fail_total 182
telemt_upstream_connect_attempts_per_request{bucket="1"} 69396
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32811
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32915
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1394
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2094
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 182
telemt_me_keepalive_timeout_total 1383
telemt_me_reconnect_attempts_total 4781
telemt_me_reconnect_success_total 1927
telemt_me_reader_eof_total 1679
telemt_me_idle_close_by_peer_total 1678
telemt_me_route_drop_no_conn_total 5167534
telemt_me_route_drop_channel_closed_total 367
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7974953
telemt_me_endpoint_quarantine_total 1100
telemt_me_single_endpoint_outage_enter_total 32
telemt_me_single_endpoint_outage_exit_total 32
telemt_me_single_endpoint_outage_reconnect_attempt_total 33
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 33
telemt_me_single_endpoint_shadow_rotate_total 1190
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 56
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
telemt_desync_total 36654
telemt_desync_full_logged_total 12127
telemt_desync_suppressed_total 24527
telemt_desync_frames_bucket_total{bucket="1_2"} 9275
telemt_desync_frames_bucket_total{bucket="3_10"} 14020
telemt_desync_frames_bucket_total{bucket="gt_10"} 13359
telemt_pool_swap_total 169
telemt_pool_force_close_total 5266
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 688
telemt_me_draining_writers_reap_progress_total 51869
telemt_me_writer_removed_unexpected_total 1821
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5196
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 48407
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4724
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 542
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 46603
telemt_me_writer_teardown_success_total{mode="normal"} 53603
telemt_me_writer_teardown_noop_total 51940
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 100046
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 102565
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 103468
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 104493
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 105064
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 105276
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 105404
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 105435
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 105443
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 105456
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 105489
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 105492
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 105543
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3171.875263
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 105543
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 688
telemt_me_refill_failed_total 151
telemt_me_writer_restored_same_endpoint_total 1666
telemt_me_writer_restored_fallback_total 10
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 145
telemt_user_connections_total{user="hello"} 7967761
telemt_user_connections_current{user="hello"} 1393
telemt_user_octets_from_client{user="hello"} 184328017453 (171.67 GB)
telemt_user_octets_to_client{user="hello"} 3315098027613 (3.02 TB)
telemt_user_msgs_from_client{user="hello"} 46485
telemt_user_msgs_to_client{user="hello"} 113805
telemt_user_unique_ips_current{user="hello"} 517
telemt_user_unique_ips_recent_window{user="hello"} 222
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 31927.4 (8h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10367369
telemt_connections_bad_total 634253
telemt_connections_current 2229
telemt_connections_me_current 2229
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 201106
telemt_upstream_connect_attempt_total 41212
telemt_upstream_connect_success_total 39127
telemt_upstream_connect_fail_total 1480
telemt_upstream_connect_attempts_per_request{bucket="1"} 40607
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20182
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11641
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1389
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5915
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1480
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 6138
telemt_me_reconnect_success_total 782
telemt_me_reader_eof_total 484
telemt_me_idle_close_by_peer_total 484
telemt_me_route_drop_no_conn_total 25021195
telemt_me_route_drop_channel_closed_total 50
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8619705
telemt_me_endpoint_quarantine_total 202
telemt_me_single_endpoint_outage_enter_total 59
telemt_me_single_endpoint_outage_exit_total 59
telemt_me_single_endpoint_outage_reconnect_attempt_total 110
telemt_me_single_endpoint_outage_reconnect_success_total 32
telemt_me_single_endpoint_quarantine_bypass_total 110
telemt_me_single_endpoint_shadow_rotate_total 252
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 22
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
telemt_desync_total 13665
telemt_desync_full_logged_total 3550
telemt_desync_suppressed_total 10115
telemt_desync_frames_bucket_total{bucket="1_2"} 2524
telemt_desync_frames_bucket_total{bucket="3_10"} 5530
telemt_desync_frames_bucket_total{bucket="gt_10"} 5611
telemt_pool_swap_total 31
telemt_pool_force_close_total 1186
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 381
telemt_me_draining_writers_reap_progress_total 8940
telemt_me_writer_removed_unexpected_total 687
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1425
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 8164
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 904
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 282
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 7754
telemt_me_writer_teardown_success_total{mode="normal"} 9589
telemt_me_writer_teardown_noop_total 8945
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 15654
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 17019
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 17499
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 18104
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 18383
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 18485
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 18534
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 18534
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 18534
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 18534
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 18534
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 18534
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 18534
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 40.892469
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 18534
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 381
telemt_me_refill_failed_total 296
telemt_me_writer_restored_same_endpoint_total 523
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 86
telemt_me_async_recovery_trigger_total 3059
telemt_me_writer_removed_unexpected_minus_restored_total 160
telemt_user_connections_total{user="hello"} 8641432
telemt_user_connections_current{user="hello"} 2229
telemt_user_octets_from_client{user="hello"} 70929291743 (66.06 GB)
telemt_user_octets_to_client{user="hello"} 359326899233 (334.65 GB)
telemt_user_msgs_from_client{user="hello"} 57283
telemt_user_msgs_to_client{user="hello"} 45481
telemt_user_unique_ips_current{user="hello"} 831
telemt_user_unique_ips_recent_window{user="hello"} 312
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 161653.9 (44h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10384488
telemt_connections_bad_total 873570
telemt_connections_current 1962
telemt_connections_me_current 1962
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 230130
telemt_upstream_connect_attempt_total 98937
telemt_upstream_connect_success_total 97912
telemt_upstream_connect_fail_total 870
telemt_upstream_connect_attempts_per_request{bucket="1"} 98782
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 60269
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36089
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1316
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 870
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 72092
telemt_me_reconnect_success_total 2665
telemt_me_reader_eof_total 2366
telemt_me_idle_close_by_peer_total 2364
telemt_me_route_drop_no_conn_total 5103425
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8192838
telemt_me_endpoint_quarantine_total 1085
telemt_me_single_endpoint_outage_enter_total 38
telemt_me_single_endpoint_outage_exit_total 38
telemt_me_single_endpoint_outage_reconnect_attempt_total 40
telemt_me_single_endpoint_outage_reconnect_success_total 38
telemt_me_single_endpoint_quarantine_bypass_total 40
telemt_me_single_endpoint_shadow_rotate_total 1205
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 49
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
telemt_desync_total 43026
telemt_desync_full_logged_total 14679
telemt_desync_suppressed_total 28347
telemt_desync_frames_bucket_total{bucket="1_2"} 8754
telemt_desync_frames_bucket_total{bucket="3_10"} 16605
telemt_desync_frames_bucket_total{bucket="gt_10"} 17667
telemt_pool_swap_total 165
telemt_pool_force_close_total 4907
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 616
telemt_me_draining_writers_reap_progress_total 54984
telemt_me_writer_removed_unexpected_total 2408
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5875
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 51539
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4221
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 686
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 50077
telemt_me_writer_teardown_success_total{mode="normal"} 57414
telemt_me_writer_teardown_noop_total 54985
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 110380
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 111699
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 112083
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 112355
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 112389
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 112392
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 112392
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 112395
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 112399
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 112399
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 112399
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 112399
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 112399
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 16.596122
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 112399
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 616
telemt_me_refill_failed_total 4279
telemt_me_writer_restored_same_endpoint_total 2233
telemt_me_writer_restored_fallback_total 46
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7365
telemt_me_writer_removed_unexpected_minus_restored_total 129
telemt_user_connections_total{user="hello"} 8196569
telemt_user_connections_current{user="hello"} 1962
telemt_user_octets_from_client{user="hello"} 186208484917 (173.42 GB)
telemt_user_octets_to_client{user="hello"} 3093806926728 (2.81 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 747
telemt_user_unique_ips_recent_window{user="hello"} 284
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 98490.1 (27h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10844063
telemt_connections_bad_total 413601
telemt_connections_current 1776
telemt_connections_me_current 1776
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4522939
telemt_upstream_connect_attempt_total 47136
telemt_upstream_connect_success_total 46786
telemt_upstream_connect_fail_total 341
telemt_upstream_connect_attempts_per_request{bucket="1"} 47127
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26055
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20566
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 165
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 341
telemt_me_reconnect_attempts_total 48217
telemt_me_reconnect_success_total 1561
telemt_me_reader_eof_total 1220
telemt_me_idle_close_by_peer_total 1219
telemt_me_route_drop_no_conn_total 3955906
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5209181
telemt_me_endpoint_quarantine_total 639
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 58
telemt_me_single_endpoint_outage_reconnect_success_total 18
telemt_me_single_endpoint_quarantine_bypass_total 58
telemt_me_single_endpoint_shadow_rotate_total 742
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 22
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
telemt_me_writers_active_current 44
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 28878
telemt_desync_full_logged_total 9788
telemt_desync_suppressed_total 19090
telemt_desync_frames_bucket_total{bucket="1_2"} 5829
telemt_desync_frames_bucket_total{bucket="3_10"} 11394
telemt_desync_frames_bucket_total{bucket="gt_10"} 11655
telemt_pool_swap_total 104
telemt_pool_force_close_total 3194
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 332
telemt_me_draining_writers_reap_progress_total 33951
telemt_me_writer_removed_unexpected_total 1281
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3044
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 32220
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2773
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 421
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 30757
telemt_me_writer_teardown_success_total{mode="normal"} 35264
telemt_me_writer_teardown_noop_total 33958
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 68046
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 68726
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 68995
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 69222
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 69222
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 69222
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 69222
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 69222
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 69222
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 69222
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 69222
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 69222
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 69222
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.082545
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 69222
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 332
telemt_me_refill_failed_total 2712
telemt_me_writer_restored_same_endpoint_total 1387
telemt_me_writer_restored_fallback_total 16
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4330
telemt_user_connections_total{user="hello"} 5202454
telemt_user_connections_current{user="hello"} 1776
telemt_user_octets_from_client{user="hello"} 112340286424 (104.63 GB)
telemt_user_octets_to_client{user="hello"} 1975411219174 (1.80 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 637
telemt_user_unique_ips_recent_window{user="hello"} 268
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 79460.7 (22h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1113675
telemt_connections_bad_total 17875
telemt_connections_current 1318
telemt_connections_me_current 1318
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 20889
telemt_upstream_connect_attempt_total 38545
telemt_upstream_connect_success_total 38434
telemt_upstream_connect_fail_total 87
telemt_upstream_connect_attempts_per_request{bucket="1"} 38521
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17421
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20419
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 594
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 87
telemt_me_reconnect_attempts_total 1745
telemt_me_reconnect_success_total 738
telemt_me_reader_eof_total 713
telemt_me_idle_close_by_peer_total 713
telemt_me_route_drop_no_conn_total 389306
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 991261
telemt_me_endpoint_quarantine_total 676
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 655
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 15
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
telemt_desync_total 5665
telemt_desync_full_logged_total 1726
telemt_desync_suppressed_total 3939
telemt_desync_frames_bucket_total{bucket="1_2"} 1344
telemt_desync_frames_bucket_total{bucket="3_10"} 2228
telemt_desync_frames_bucket_total{bucket="gt_10"} 2093
telemt_pool_swap_total 85
telemt_pool_force_close_total 2178
telemt_me_writer_close_signal_drop_total 125
telemt_me_draining_writers_reap_progress_total 31974
telemt_me_writer_removed_unexpected_total 688
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2475
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 30214
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2095
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 83
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 29796
telemt_me_writer_teardown_success_total{mode="normal"} 32689
telemt_me_writer_teardown_noop_total 31977
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 63979
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 64471
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 64635
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 64666
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 64666
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 64666
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 64666
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 64666
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 64666
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 64666
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 64666
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 64666
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 64666
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.815247
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 64666
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 125
telemt_me_refill_failed_total 55
telemt_me_writer_restored_same_endpoint_total 628
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 987669
telemt_user_connections_current{user="hello"} 1318
telemt_user_octets_from_client{user="hello"} 18274958921 (17.02 GB)
telemt_user_octets_to_client{user="hello"} 426121838427 (396.86 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 446
telemt_user_unique_ips_recent_window{user="hello"} 238
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 161658.5 (44h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12669213
telemt_connections_bad_total 1469935
telemt_connections_current 1745
telemt_connections_me_current 1745
telemt_handshake_timeouts_total 354091
telemt_upstream_connect_attempt_total 60842
telemt_upstream_connect_success_total 60556
telemt_upstream_connect_fail_total 188
telemt_upstream_connect_attempts_per_request{bucket="1"} 60744
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29863
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30609
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 82
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 188
telemt_me_reconnect_attempts_total 2384
telemt_me_reconnect_success_total 1264
telemt_me_reader_eof_total 1227
telemt_me_idle_close_by_peer_total 1227
telemt_me_route_drop_no_conn_total 4241007
telemt_me_route_drop_channel_closed_total 121
telemt_me_route_drop_queue_full_total 37
telemt_me_route_drop_queue_full_profile_total{profile="high"} 37
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9583337
telemt_me_endpoint_quarantine_total 1083
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1208
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 41
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
telemt_desync_total 39370
telemt_desync_full_logged_total 12850
telemt_desync_suppressed_total 26520
telemt_desync_frames_bucket_total{bucket="1_2"} 9385
telemt_desync_frames_bucket_total{bucket="3_10"} 14568
telemt_desync_frames_bucket_total{bucket="gt_10"} 15417
telemt_pool_swap_total 179
telemt_pool_force_close_total 4937
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 632
telemt_me_draining_writers_reap_progress_total 54742
telemt_me_writer_removed_unexpected_total 1179
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4504
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 51451
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4763
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 49805
telemt_me_writer_teardown_success_total{mode="normal"} 55955
telemt_me_writer_teardown_noop_total 54744
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 108259
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 109876
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 110236
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 110566
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 110686
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 110699
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 110699
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 110699
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 110699
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 110699
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 110699
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 110699
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 110699
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 18.508967
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 110699
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 632
telemt_me_refill_failed_total 59
telemt_me_writer_restored_same_endpoint_total 1104
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 63
telemt_user_connections_total{user="hello"} 9552441
telemt_user_connections_current{user="hello"} 1745
telemt_user_octets_from_client{user="hello"} 187287195100 (174.42 GB)
telemt_user_octets_to_client{user="hello"} 4219313211272 (3.84 TB)
telemt_user_unique_ips_current{user="hello"} 610
telemt_user_unique_ips_recent_window{user="hello"} 311
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 161655.1 (44h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10986681
telemt_connections_bad_total 1227515
telemt_connections_current 1737
telemt_connections_me_current 1737
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 285039
telemt_upstream_connect_attempt_total 86745
telemt_upstream_connect_success_total 86016
telemt_upstream_connect_fail_total 575
telemt_upstream_connect_attempts_per_request{bucket="1"} 86591
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 47255
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35804
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 910
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2047
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 575
telemt_me_reconnect_attempts_total 9131
telemt_me_reconnect_success_total 2154
telemt_me_reader_eof_total 2009
telemt_me_idle_close_by_peer_total 2009
telemt_me_seq_mismatch_total 76
telemt_me_route_drop_no_conn_total 5484240
telemt_me_route_drop_channel_closed_total 351
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8499208
telemt_me_endpoint_quarantine_total 1223
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 42
telemt_me_single_endpoint_outage_exit_total 42
telemt_me_single_endpoint_outage_reconnect_attempt_total 42
telemt_me_single_endpoint_outage_reconnect_success_total 40
telemt_me_single_endpoint_quarantine_bypass_total 42
telemt_me_single_endpoint_shadow_rotate_total 1209
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 51
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
telemt_me_writers_active_current 92
telemt_desync_total 38721
telemt_desync_full_logged_total 12505
telemt_desync_suppressed_total 26216
telemt_desync_frames_bucket_total{bucket="1_2"} 9629
telemt_desync_frames_bucket_total{bucket="3_10"} 14424
telemt_desync_frames_bucket_total{bucket="gt_10"} 14668
telemt_pool_swap_total 170
telemt_pool_force_close_total 4752
telemt_pool_stale_pick_total 360
telemt_me_writer_close_signal_drop_total 613
telemt_me_draining_writers_reap_progress_total 54204
telemt_me_writer_removed_unexpected_total 2035
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5653
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 50656
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4313
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 439
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 49452
telemt_me_writer_teardown_success_total{mode="normal"} 56309
telemt_me_writer_teardown_noop_total 54209
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 107966
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 109637
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 110151
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 110468
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 110518
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 110518
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 110518
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 110518
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 110518
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 110518
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 110518
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 110518
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 110518
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 16.716597
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 110518
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 613
telemt_me_refill_failed_total 358
telemt_me_writer_restored_same_endpoint_total 1752
telemt_me_writer_restored_fallback_total 102
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 128
telemt_me_writer_removed_unexpected_minus_restored_total 181
telemt_user_connections_total{user="hello"} 8505122
telemt_user_connections_current{user="hello"} 1737
telemt_user_octets_from_client{user="hello"} 149497720037 (139.23 GB)
telemt_user_octets_to_client{user="hello"} 3257619994063 (2.96 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 684
telemt_user_unique_ips_recent_window{user="hello"} 285
```