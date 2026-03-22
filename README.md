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

# Server Metrics 2026-03-22 05:19:23 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 29579.3 (8h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 504658
telemt_connections_bad_total 34107
telemt_connections_current 1169
telemt_connections_me_current 1169
telemt_handshake_timeouts_total 27210
telemt_upstream_connect_attempt_total 12248
telemt_upstream_connect_success_total 12247
telemt_upstream_connect_attempts_per_request{bucket="1"} 12247
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4295
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7922
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_reconnect_attempts_total 321
telemt_me_reconnect_success_total 191
telemt_me_reader_eof_total 186
telemt_me_idle_close_by_peer_total 186
telemt_me_route_drop_no_conn_total 107196
telemt_me_route_drop_channel_closed_total 28
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 416627
telemt_me_endpoint_quarantine_total 228
telemt_me_single_endpoint_shadow_rotate_total 245
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
telemt_me_writers_active_current 48
telemt_desync_total 3701
telemt_desync_full_logged_total 1005
telemt_desync_suppressed_total 2696
telemt_desync_frames_bucket_total{bucket="1_2"} 1253
telemt_desync_frames_bucket_total{bucket="3_10"} 1410
telemt_desync_frames_bucket_total{bucket="gt_10"} 1038
telemt_pool_swap_total 32
telemt_pool_force_close_total 845
telemt_me_writer_close_signal_drop_total 73
telemt_me_draining_writers_reap_progress_total 11082
telemt_me_writer_removed_unexpected_total 184
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 752
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 10504
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 840
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 10237
telemt_me_writer_teardown_success_total{mode="normal"} 11256
telemt_me_writer_teardown_noop_total 11083
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 21538
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 21917
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 22076
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 22227
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 22305
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 22339
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 22339
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 22339
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 22339
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 22339
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 22339
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 22339
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 22339
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.021343
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 22339
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 73
telemt_me_refill_failed_total 7
telemt_me_writer_restored_same_endpoint_total 173
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 415668
telemt_user_connections_current{user="hello"} 1169
telemt_user_octets_from_client{user="hello"} 5597666616 (5.21 GB)
telemt_user_octets_to_client{user="hello"} 146710274696 (136.63 GB)
telemt_user_unique_ips_current{user="hello"} 482
telemt_user_unique_ips_recent_window{user="hello"} 180
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 42945.4 (11h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 959566
telemt_connections_bad_total 72666
telemt_connections_current 1160
telemt_connections_me_current 1160
telemt_handshake_timeouts_total 32597
telemt_upstream_connect_attempt_total 22970
telemt_upstream_connect_success_total 22651
telemt_upstream_connect_fail_total 288
telemt_upstream_connect_attempts_per_request{bucket="1"} 22939
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11604
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10999
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 288
telemt_me_reconnect_attempts_total 1729
telemt_me_reconnect_success_total 629
telemt_me_reader_eof_total 550
telemt_me_idle_close_by_peer_total 550
telemt_me_route_drop_no_conn_total 371914
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 747578
telemt_me_endpoint_quarantine_total 406
telemt_me_single_endpoint_outage_enter_total 21
telemt_me_single_endpoint_outage_exit_total 21
telemt_me_single_endpoint_outage_reconnect_attempt_total 21
telemt_me_single_endpoint_outage_reconnect_success_total 21
telemt_me_single_endpoint_quarantine_bypass_total 21
telemt_me_single_endpoint_shadow_rotate_total 349
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
telemt_me_writers_active_current 41
telemt_desync_total 3224
telemt_desync_full_logged_total 1862
telemt_desync_suppressed_total 1362
telemt_desync_frames_bucket_total{bucket="1_2"} 675
telemt_desync_frames_bucket_total{bucket="3_10"} 1237
telemt_desync_frames_bucket_total{bucket="gt_10"} 1312
telemt_pool_swap_total 46
telemt_pool_force_close_total 1206
telemt_me_writer_close_signal_drop_total 87
telemt_me_draining_writers_reap_progress_total 17787
telemt_me_writer_removed_unexpected_total 525
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1519
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16805
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1184
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 22
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16581
telemt_me_writer_teardown_success_total{mode="normal"} 18324
telemt_me_writer_teardown_noop_total 17787
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 35536
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 35874
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 35998
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 36097
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 36109
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 36111
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 36111
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 36111
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 36111
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 36111
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 36111
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 36111
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 36111
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.091462
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 36111
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 87
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 470
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 749311
telemt_user_connections_current{user="hello"} 1160
telemt_user_octets_from_client{user="hello"} 12009742215 (11.18 GB)
telemt_user_octets_to_client{user="hello"} 273705582946 (254.91 GB)
telemt_user_msgs_from_client{user="hello"} 6021
telemt_user_msgs_to_client{user="hello"} 9976
telemt_user_unique_ips_current{user="hello"} 714
telemt_user_unique_ips_recent_window{user="hello"} 267
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 117805.2 (32h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8211782
telemt_connections_bad_total 709239
telemt_connections_current 3213
telemt_connections_me_current 3213
telemt_handshake_timeouts_total 267891
telemt_upstream_connect_attempt_total 43895
telemt_upstream_connect_success_total 43817
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 43825
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19842
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23787
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 182
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1644
telemt_me_reconnect_success_total 860
telemt_me_reader_eof_total 868
telemt_me_idle_close_by_peer_total 868
telemt_me_route_drop_no_conn_total 4624754
telemt_me_route_drop_channel_closed_total 67
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6596301
telemt_me_endpoint_quarantine_total 752
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 886
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 28
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
telemt_desync_total 27846
telemt_desync_full_logged_total 9272
telemt_desync_suppressed_total 18574
telemt_desync_frames_bucket_total{bucket="1_2"} 6018
telemt_desync_frames_bucket_total{bucket="3_10"} 10900
telemt_desync_frames_bucket_total{bucket="gt_10"} 10928
telemt_pool_swap_total 127
telemt_pool_force_close_total 4174
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 631
telemt_me_draining_writers_reap_progress_total 40066
telemt_me_writer_removed_unexpected_total 836
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3312
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 37119
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3930
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 244
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 35892
telemt_me_writer_teardown_success_total{mode="normal"} 40431
telemt_me_writer_teardown_noop_total 40110
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 73984
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 75925
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 76976
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 78561
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 79656
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 80240
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 80530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 80541
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 80541
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 80541
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 80541
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 80541
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 80541
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 166.428356
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 80541
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 631
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 767
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 64
telemt_user_connections_total{user="hello"} 6587880
telemt_user_connections_current{user="hello"} 3213
telemt_user_octets_from_client{user="hello"} 111652205584 (103.98 GB)
telemt_user_octets_to_client{user="hello"} 2233625923604 (2.03 TB)
telemt_user_unique_ips_current{user="hello"} 1439
telemt_user_unique_ips_recent_window{user="hello"} 416
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 117806.6 (32h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6765982
telemt_connections_bad_total 600001
telemt_connections_current 2807
telemt_connections_me_current 2807
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 225443
telemt_upstream_connect_attempt_total 47800
telemt_upstream_connect_success_total 47401
telemt_upstream_connect_fail_total 202
telemt_upstream_connect_attempts_per_request{bucket="1"} 47603
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23406
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23404
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 558
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 202
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 2048
telemt_me_reconnect_success_total 924
telemt_me_reader_eof_total 902
telemt_me_idle_close_by_peer_total 902
telemt_me_route_drop_no_conn_total 2328961
telemt_me_route_drop_channel_closed_total 286
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5060063
telemt_me_endpoint_quarantine_total 743
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 908
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
telemt_desync_total 23521
telemt_desync_full_logged_total 8069
telemt_desync_suppressed_total 15452
telemt_desync_frames_bucket_total{bucket="1_2"} 5639
telemt_desync_frames_bucket_total{bucket="3_10"} 9134
telemt_desync_frames_bucket_total{bucket="gt_10"} 8748
telemt_pool_swap_total 128
telemt_pool_force_close_total 3794
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 389
telemt_me_draining_writers_reap_progress_total 38455
telemt_me_writer_removed_unexpected_total 881
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3178
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 36101
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3576
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 218
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 34661
telemt_me_writer_teardown_success_total{mode="normal"} 39279
telemt_me_writer_teardown_noop_total 38461
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 74278
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 75916
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 76523
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 77120
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 77535
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 77720
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 77740
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 77740
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 77740
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 77740
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 77740
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 77740
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 77740
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 49.375677
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 77740
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 389
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 806
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 65
telemt_user_connections_total{user="hello"} 4981580
telemt_user_connections_current{user="hello"} 2807
telemt_user_octets_from_client{user="hello"} 145818411537 (135.80 GB)
telemt_user_octets_to_client{user="hello"} 2379695527391 (2.16 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1179
telemt_user_unique_ips_recent_window{user="hello"} 365
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 117772.8 (32h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6611751
telemt_connections_bad_total 560151
telemt_connections_current 2251
telemt_connections_me_current 2251
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 219784
telemt_upstream_connect_attempt_total 54282
telemt_upstream_connect_success_total 53740
telemt_upstream_connect_fail_total 143
telemt_upstream_connect_attempts_per_request{bucket="1"} 53883
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26852
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24969
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 732
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1187
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 143
telemt_me_keepalive_timeout_total 72
telemt_me_reconnect_attempts_total 2407
telemt_me_reconnect_success_total 1066
telemt_me_reader_eof_total 1001
telemt_me_idle_close_by_peer_total 1001
telemt_me_route_drop_no_conn_total 2329904
telemt_me_route_drop_channel_closed_total 140
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4918846
telemt_me_endpoint_quarantine_total 837
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 876
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
telemt_me_writers_active_current 46
telemt_desync_total 23421
telemt_desync_full_logged_total 7940
telemt_desync_suppressed_total 15481
telemt_desync_frames_bucket_total{bucket="1_2"} 5699
telemt_desync_frames_bucket_total{bucket="3_10"} 8976
telemt_desync_frames_bucket_total{bucket="gt_10"} 8746
telemt_pool_swap_total 126
telemt_pool_force_close_total 3662
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 413
telemt_me_draining_writers_reap_progress_total 39558
telemt_me_writer_removed_unexpected_total 991
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3395
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 37174
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3425
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 237
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 35896
telemt_me_writer_teardown_success_total{mode="normal"} 40569
telemt_me_writer_teardown_noop_total 39570
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 77256
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 78761
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 79256
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 79796
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 80051
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 80106
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 80139
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 80139
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 80139
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 80139
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 80139
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 80139
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 80139
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 33.965765
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 80139
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 413
telemt_me_refill_failed_total 74
telemt_me_writer_restored_same_endpoint_total 932
telemt_me_writer_restored_fallback_total 5
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 54
telemt_user_connections_total{user="hello"} 4913379
telemt_user_connections_current{user="hello"} 2251
telemt_user_octets_from_client{user="hello"} 137035055243 (127.62 GB)
telemt_user_octets_to_client{user="hello"} 2247464868063 (2.04 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 993
telemt_user_unique_ips_recent_window{user="hello"} 329
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 117809.8 (32h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21149118
telemt_connections_bad_total 1790093
telemt_connections_current 3932
telemt_connections_me_current 3932
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 643515
telemt_upstream_connect_attempt_total 204919
telemt_upstream_connect_success_total 186577
telemt_upstream_connect_fail_total 16479
telemt_upstream_connect_attempts_per_request{bucket="1"} 203056
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 130991
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 45408
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1224
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8954
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16479
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 65269
telemt_me_reconnect_success_total 2487
telemt_me_reader_eof_total 1576
telemt_me_idle_close_by_peer_total 1575
telemt_me_route_drop_no_conn_total 40008636
telemt_me_route_drop_channel_closed_total 129
telemt_me_route_drop_queue_full_total 13
telemt_me_route_drop_queue_full_profile_total{profile="high"} 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16996590
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 911
telemt_me_single_endpoint_outage_enter_total 144
telemt_me_single_endpoint_outage_exit_total 144
telemt_me_single_endpoint_outage_reconnect_attempt_total 297
telemt_me_single_endpoint_outage_reconnect_success_total 76
telemt_me_single_endpoint_quarantine_bypass_total 297
telemt_me_single_endpoint_shadow_rotate_total 921
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 68
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
telemt_desync_total 32982
telemt_desync_full_logged_total 9945
telemt_desync_suppressed_total 23037
telemt_desync_frames_bucket_total{bucket="1_2"} 7191
telemt_desync_frames_bucket_total{bucket="3_10"} 14639
telemt_desync_frames_bucket_total{bucket="gt_10"} 11152
telemt_pool_swap_total 121
telemt_pool_force_close_total 3916
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 846
telemt_me_draining_writers_reap_progress_total 37115
telemt_me_writer_removed_unexpected_total 2313
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4978
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 34197
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 24
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3358
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 558
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 33199
telemt_me_writer_teardown_success_total{mode="normal"} 39175
telemt_me_writer_teardown_noop_total 37142
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 69224
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 71828
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 73167
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 74910
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 75871
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 76213
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 76298
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 76300
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 76303
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 76308
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 76308
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 76312
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 76317
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 218.214989
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 76317
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 846
telemt_me_refill_failed_total 3811
telemt_me_writer_restored_same_endpoint_total 1707
telemt_me_writer_restored_fallback_total 22
telemt_me_no_writer_failfast_total 666
telemt_me_async_recovery_trigger_total 14678
telemt_me_writer_removed_unexpected_minus_restored_total 584
telemt_user_connections_total{user="hello"} 17131146
telemt_user_connections_current{user="hello"} 3932
telemt_user_octets_from_client{user="hello"} 250874773752 (233.65 GB)
telemt_user_octets_to_client{user="hello"} 1321620794319 (1.20 TB)
telemt_user_msgs_from_client{user="hello"} 398569
telemt_user_msgs_to_client{user="hello"} 788102
telemt_user_unique_ips_current{user="hello"} 1567
telemt_user_unique_ips_recent_window{user="hello"} 560
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 117777.2 (32h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6386833
telemt_connections_bad_total 610128
telemt_connections_current 2740
telemt_connections_me_current 2740
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 134950
telemt_upstream_connect_attempt_total 62826
telemt_upstream_connect_success_total 62100
telemt_upstream_connect_fail_total 620
telemt_upstream_connect_attempts_per_request{bucket="1"} 62720
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35797
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25943
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 359
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 620
telemt_me_reconnect_attempts_total 69885
telemt_me_reconnect_success_total 1880
telemt_me_reader_eof_total 1653
telemt_me_idle_close_by_peer_total 1652
telemt_me_route_drop_no_conn_total 2465430
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4964705
telemt_me_endpoint_quarantine_total 796
telemt_me_single_endpoint_outage_enter_total 23
telemt_me_single_endpoint_outage_exit_total 23
telemt_me_single_endpoint_outage_reconnect_attempt_total 24
telemt_me_single_endpoint_outage_reconnect_success_total 23
telemt_me_single_endpoint_quarantine_bypass_total 24
telemt_me_single_endpoint_shadow_rotate_total 895
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
telemt_me_writers_active_current 43
telemt_desync_total 24760
telemt_desync_full_logged_total 8679
telemt_desync_suppressed_total 16081
telemt_desync_frames_bucket_total{bucket="1_2"} 4884
telemt_desync_frames_bucket_total{bucket="3_10"} 9554
telemt_desync_frames_bucket_total{bucket="gt_10"} 10322
telemt_pool_swap_total 122
telemt_pool_force_close_total 3490
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 413
telemt_me_draining_writers_reap_progress_total 41623
telemt_me_writer_removed_unexpected_total 1689
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4208
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 39136
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3084
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 406
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 38133
telemt_me_writer_teardown_success_total{mode="normal"} 43344
telemt_me_writer_teardown_noop_total 41624
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 83606
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 84482
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 84774
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 84936
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 84965
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 84968
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 84968
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 84968
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 84968
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 84968
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 84968
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 84968
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 84968
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.952871
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 84968
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 413
telemt_me_refill_failed_total 4213
telemt_me_writer_restored_same_endpoint_total 1570
telemt_me_writer_restored_fallback_total 38
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7313
telemt_me_writer_removed_unexpected_minus_restored_total 81
telemt_user_connections_total{user="hello"} 4956823
telemt_user_connections_current{user="hello"} 2740
telemt_user_octets_from_client{user="hello"} 129106548276 (120.24 GB)
telemt_user_octets_to_client{user="hello"} 2057074548506 (1.87 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 1204
telemt_user_unique_ips_recent_window{user="hello"} 353
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 54613.1 (15h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4381174
telemt_connections_bad_total 183152
telemt_connections_current 2288
telemt_connections_me_current 2288
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 1732509
telemt_upstream_connect_attempt_total 31675
telemt_upstream_connect_success_total 31464
telemt_upstream_connect_fail_total 204
telemt_upstream_connect_attempts_per_request{bucket="1"} 31668
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19158
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12223
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 83
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 204
telemt_me_reconnect_attempts_total 46080
telemt_me_reconnect_success_total 1031
telemt_me_reader_eof_total 720
telemt_me_idle_close_by_peer_total 720
telemt_me_route_drop_no_conn_total 1103925
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2166924
telemt_me_endpoint_quarantine_total 392
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 50
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 50
telemt_me_single_endpoint_shadow_rotate_total 423
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
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 11769
telemt_desync_full_logged_total 4029
telemt_desync_suppressed_total 7740
telemt_desync_frames_bucket_total{bucket="1_2"} 2269
telemt_desync_frames_bucket_total{bucket="3_10"} 4508
telemt_desync_frames_bucket_total{bucket="gt_10"} 4992
telemt_pool_swap_total 59
telemt_pool_force_close_total 1730
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 153
telemt_me_draining_writers_reap_progress_total 20316
telemt_me_writer_removed_unexpected_total 791
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1743
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19393
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1521
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 209
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18586
telemt_me_writer_teardown_success_total{mode="normal"} 21136
telemt_me_writer_teardown_noop_total 20318
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 40892
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 41191
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 41348
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 41454
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 41454
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 41454
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 41454
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 41454
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 41454
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 41454
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 41454
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 41454
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 41454
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.696231
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 41454
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 153
telemt_me_refill_failed_total 2617
telemt_me_writer_restored_same_endpoint_total 919
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4264
telemt_user_connections_total{user="hello"} 2169392
telemt_user_connections_current{user="hello"} 2288
telemt_user_octets_from_client{user="hello"} 58115136016 (54.12 GB)
telemt_user_octets_to_client{user="hello"} 948773500754 (883.61 GB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 1062
telemt_user_unique_ips_recent_window{user="hello"} 344
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 35584.3 (9h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 251999
telemt_connections_bad_total 1928
telemt_connections_current 563
telemt_connections_me_current 563
telemt_handshake_timeouts_total 6537
telemt_upstream_connect_attempt_total 17215
telemt_upstream_connect_success_total 17172
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 17211
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7235
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9842
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 95
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_reconnect_attempts_total 413
telemt_me_reconnect_success_total 235
telemt_me_reader_eof_total 235
telemt_me_idle_close_by_peer_total 235
telemt_me_route_drop_no_conn_total 70432
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 224520
telemt_me_endpoint_quarantine_total 345
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 310
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 5
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
telemt_desync_total 1210
telemt_desync_full_logged_total 330
telemt_desync_suppressed_total 880
telemt_desync_frames_bucket_total{bucket="1_2"} 424
telemt_desync_frames_bucket_total{bucket="3_10"} 464
telemt_desync_frames_bucket_total{bucket="gt_10"} 322
telemt_pool_swap_total 39
telemt_pool_force_close_total 868
telemt_me_writer_close_signal_drop_total 34
telemt_me_draining_writers_reap_progress_total 15582
telemt_me_writer_removed_unexpected_total 224
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 988
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14829
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 866
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14714
telemt_me_writer_teardown_success_total{mode="normal"} 15817
telemt_me_writer_teardown_noop_total 15582
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 31137
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 31371
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 31389
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 31399
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 31399
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 31399
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 31399
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 31399
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 31399
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 31399
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 31399
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 31399
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 31399
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.248995
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 31399
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 34
telemt_me_refill_failed_total 10
telemt_me_writer_restored_same_endpoint_total 203
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 224156
telemt_user_connections_current{user="hello"} 563
telemt_user_octets_from_client{user="hello"} 3755442716 (3.50 GB)
telemt_user_octets_to_client{user="hello"} 138034969936 (128.56 GB)
telemt_user_unique_ips_current{user="hello"} 223
telemt_user_unique_ips_recent_window{user="hello"} 79
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 117781.8 (32h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7737675
telemt_connections_bad_total 769994
telemt_connections_current 3018
telemt_connections_me_current 3018
telemt_handshake_timeouts_total 220393
telemt_upstream_connect_attempt_total 46437
telemt_upstream_connect_success_total 46267
telemt_upstream_connect_fail_total 133
telemt_upstream_connect_attempts_per_request{bucket="1"} 46400
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22872
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23354
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 133
telemt_me_reconnect_attempts_total 1689
telemt_me_reconnect_success_total 905
telemt_me_reader_eof_total 899
telemt_me_idle_close_by_peer_total 899
telemt_me_route_drop_no_conn_total 2198352
telemt_me_route_drop_channel_closed_total 52
telemt_me_route_drop_queue_full_total 23
telemt_me_route_drop_queue_full_profile_total{profile="high"} 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5768238
telemt_me_endpoint_quarantine_total 841
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 904
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
telemt_desync_total 22564
telemt_desync_full_logged_total 7440
telemt_desync_suppressed_total 15124
telemt_desync_frames_bucket_total{bucket="1_2"} 5654
telemt_desync_frames_bucket_total{bucket="3_10"} 8192
telemt_desync_frames_bucket_total{bucket="gt_10"} 8718
telemt_pool_swap_total 130
telemt_pool_force_close_total 3464
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 410
telemt_me_draining_writers_reap_progress_total 41911
telemt_me_writer_removed_unexpected_total 862
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3271
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 39529
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3376
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 38447
telemt_me_writer_teardown_success_total{mode="normal"} 42800
telemt_me_writer_teardown_noop_total 41913
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 83313
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 84244
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 84425
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 84625
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 84713
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 84713
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 84713
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 84713
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 84713
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 84713
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 84713
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 84713
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 84713
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.841332
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 84713
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 410
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 810
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 44
telemt_user_connections_total{user="hello"} 5742851
telemt_user_connections_current{user="hello"} 3018
telemt_user_octets_from_client{user="hello"} 113616817208 (105.81 GB)
telemt_user_octets_to_client{user="hello"} 2685392838096 (2.44 TB)
telemt_user_unique_ips_current{user="hello"} 1184
telemt_user_unique_ips_recent_window{user="hello"} 396
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 117778.1 (32h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6720657
telemt_connections_bad_total 658121
telemt_connections_current 2989
telemt_connections_me_current 2989
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 182222
telemt_upstream_connect_attempt_total 62277
telemt_upstream_connect_success_total 61808
telemt_upstream_connect_fail_total 409
telemt_upstream_connect_attempts_per_request{bucket="1"} 62217
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35724
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24950
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 616
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 409
telemt_me_reconnect_attempts_total 5773
telemt_me_reconnect_success_total 1275
telemt_me_reader_eof_total 1145
telemt_me_idle_close_by_peer_total 1145
telemt_me_seq_mismatch_total 54
telemt_me_route_drop_no_conn_total 2253391
telemt_me_route_drop_channel_closed_total 191
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5135536
telemt_me_endpoint_quarantine_total 928
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 29
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 29
telemt_me_single_endpoint_shadow_rotate_total 902
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
telemt_desync_total 21398
telemt_desync_full_logged_total 7113
telemt_desync_suppressed_total 14285
telemt_desync_frames_bucket_total{bucket="1_2"} 5385
telemt_desync_frames_bucket_total{bucket="3_10"} 7835
telemt_desync_frames_bucket_total{bucket="gt_10"} 8178
telemt_pool_swap_total 128
telemt_pool_force_close_total 3410
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 411
telemt_me_draining_writers_reap_progress_total 40473
telemt_me_writer_removed_unexpected_total 1157
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3825
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 37862
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3187
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 223
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 37063
telemt_me_writer_teardown_success_total{mode="normal"} 41687
telemt_me_writer_teardown_noop_total 40477
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 80429
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 81530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 81929
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 82126
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 82164
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 82164
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 82164
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 82164
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 82164
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 82164
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 82164
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 82164
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 82164
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 11.607516
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 82164
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 411
telemt_me_refill_failed_total 259
telemt_me_writer_restored_same_endpoint_total 998
telemt_me_writer_restored_fallback_total 72
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 82
telemt_me_writer_removed_unexpected_minus_restored_total 87
telemt_user_connections_total{user="hello"} 5138184
telemt_user_connections_current{user="hello"} 2989
telemt_user_octets_from_client{user="hello"} 96462781201 (89.84 GB)
telemt_user_octets_to_client{user="hello"} 2218926838536 (2.02 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1215
telemt_user_unique_ips_recent_window{user="hello"} 412
```