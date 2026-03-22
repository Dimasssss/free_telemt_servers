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

# Server Metrics 2026-03-22 05:24:34 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 29885.9 (8h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 513411
telemt_connections_bad_total 34714
telemt_connections_current 1127
telemt_connections_me_current 1127
telemt_handshake_timeouts_total 27503
telemt_upstream_connect_attempt_total 12408
telemt_upstream_connect_success_total 12407
telemt_upstream_connect_attempts_per_request{bucket="1"} 12407
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4352
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8025
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_reconnect_attempts_total 326
telemt_me_reconnect_success_total 194
telemt_me_reader_eof_total 190
telemt_me_idle_close_by_peer_total 190
telemt_me_route_drop_no_conn_total 109385
telemt_me_route_drop_channel_closed_total 29
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 424152
telemt_me_endpoint_quarantine_total 232
telemt_me_single_endpoint_shadow_rotate_total 248
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
telemt_me_writers_active_current 43
telemt_desync_total 3769
telemt_desync_full_logged_total 1024
telemt_desync_suppressed_total 2745
telemt_desync_frames_bucket_total{bucket="1_2"} 1273
telemt_desync_frames_bucket_total{bucket="3_10"} 1428
telemt_desync_frames_bucket_total{bucket="gt_10"} 1068
telemt_pool_swap_total 33
telemt_pool_force_close_total 874
telemt_me_writer_close_signal_drop_total 79
telemt_me_draining_writers_reap_progress_total 11219
telemt_me_writer_removed_unexpected_total 187
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 778
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 10619
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 867
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 10345
telemt_me_writer_teardown_success_total{mode="normal"} 11397
telemt_me_writer_teardown_noop_total 11220
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 21769
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 22158
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 22328
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 22494
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 22583
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 22617
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 22617
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 22617
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 22617
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 22617
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 22617
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 22617
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 22617
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.729348
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 22617
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 79
telemt_me_refill_failed_total 7
telemt_me_writer_restored_same_endpoint_total 176
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 423178
telemt_user_connections_current{user="hello"} 1127
telemt_user_octets_from_client{user="hello"} 5656016220 (5.27 GB)
telemt_user_octets_to_client{user="hello"} 149276648592 (139.02 GB)
telemt_user_unique_ips_current{user="hello"} 428
telemt_user_unique_ips_recent_window{user="hello"} 384
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 43251.9 (12h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 967843
telemt_connections_bad_total 74025
telemt_connections_current 1428
telemt_connections_me_current 1428
telemt_handshake_timeouts_total 33013
telemt_upstream_connect_attempt_total 23076
telemt_upstream_connect_success_total 22755
telemt_upstream_connect_fail_total 289
telemt_upstream_connect_attempts_per_request{bucket="1"} 23044
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11644
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11062
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 49
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 289
telemt_me_reconnect_attempts_total 1731
telemt_me_reconnect_success_total 630
telemt_me_reader_eof_total 551
telemt_me_idle_close_by_peer_total 551
telemt_me_route_drop_no_conn_total 373584
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 753169
telemt_me_endpoint_quarantine_total 406
telemt_me_single_endpoint_outage_enter_total 21
telemt_me_single_endpoint_outage_exit_total 21
telemt_me_single_endpoint_outage_reconnect_attempt_total 21
telemt_me_single_endpoint_outage_reconnect_success_total 21
telemt_me_single_endpoint_quarantine_bypass_total 21
telemt_me_single_endpoint_shadow_rotate_total 350
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
telemt_me_writers_warm_current 12
telemt_desync_total 3254
telemt_desync_full_logged_total 1875
telemt_desync_suppressed_total 1379
telemt_desync_frames_bucket_total{bucket="1_2"} 681
telemt_desync_frames_bucket_total{bucket="3_10"} 1248
telemt_desync_frames_bucket_total{bucket="gt_10"} 1325
telemt_pool_swap_total 46
telemt_pool_force_close_total 1206
telemt_me_writer_close_signal_drop_total 87
telemt_me_draining_writers_reap_progress_total 17858
telemt_me_writer_removed_unexpected_total 526
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1521
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16875
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1184
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 22
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16652
telemt_me_writer_teardown_success_total{mode="normal"} 18396
telemt_me_writer_teardown_noop_total 17858
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 35679
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 36017
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 36141
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 36240
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 36252
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 36254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 36254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 36254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 36254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 36254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 36254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 36254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 36254
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.092318
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 36254
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 87
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 471
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 754900
telemt_user_connections_current{user="hello"} 1428
telemt_user_octets_from_client{user="hello"} 12066675743 (11.24 GB)
telemt_user_octets_to_client{user="hello"} 276611694594 (257.61 GB)
telemt_user_msgs_from_client{user="hello"} 6021
telemt_user_msgs_to_client{user="hello"} 9976
telemt_user_unique_ips_current{user="hello"} 905
telemt_user_unique_ips_recent_window{user="hello"} 452
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 118112.5 (32h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8236709
telemt_connections_bad_total 711691
telemt_connections_current 2283
telemt_connections_me_current 2283
telemt_handshake_timeouts_total 268537
telemt_upstream_connect_attempt_total 44034
telemt_upstream_connect_success_total 43956
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 43964
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19915
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23852
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 183
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1646
telemt_me_reconnect_success_total 862
telemt_me_reader_eof_total 870
telemt_me_idle_close_by_peer_total 870
telemt_me_route_drop_no_conn_total 4630104
telemt_me_route_drop_channel_closed_total 67
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6611273
telemt_me_endpoint_quarantine_total 754
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 889
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
telemt_desync_total 27940
telemt_desync_full_logged_total 9301
telemt_desync_suppressed_total 18639
telemt_desync_frames_bucket_total{bucket="1_2"} 6039
telemt_desync_frames_bucket_total{bucket="3_10"} 10935
telemt_desync_frames_bucket_total{bucket="gt_10"} 10966
telemt_pool_swap_total 128
telemt_pool_force_close_total 4206
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 639
telemt_me_draining_writers_reap_progress_total 40202
telemt_me_writer_removed_unexpected_total 838
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3323
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 37246
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3961
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 245
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 35996
telemt_me_writer_teardown_success_total{mode="normal"} 40569
telemt_me_writer_teardown_noop_total 40246
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 74197
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 76144
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 77216
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 78824
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 79930
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 80514
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 80804
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 80815
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 80815
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 80815
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 80815
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 80815
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 80815
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 167.334363
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 80815
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 639
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 769
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 64
telemt_user_connections_total{user="hello"} 6602725
telemt_user_connections_current{user="hello"} 2283
telemt_user_octets_from_client{user="hello"} 111988638716 (104.30 GB)
telemt_user_octets_to_client{user="hello"} 2240521689176 (2.04 TB)
telemt_user_unique_ips_current{user="hello"} 921
telemt_user_unique_ips_recent_window{user="hello"} 820
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 118113.5 (32h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6783262
telemt_connections_bad_total 600215
telemt_connections_current 2004
telemt_connections_me_current 2004
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 226205
telemt_upstream_connect_attempt_total 47944
telemt_upstream_connect_success_total 47544
telemt_upstream_connect_fail_total 203
telemt_upstream_connect_attempts_per_request{bucket="1"} 47747
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23481
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23472
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 558
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 203
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 2050
telemt_me_reconnect_success_total 926
telemt_me_reader_eof_total 904
telemt_me_idle_close_by_peer_total 904
telemt_me_route_drop_no_conn_total 2333856
telemt_me_route_drop_channel_closed_total 286
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5073891
telemt_me_endpoint_quarantine_total 750
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 911
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
telemt_me_writers_active_current 43
telemt_desync_total 23584
telemt_desync_full_logged_total 8084
telemt_desync_suppressed_total 15500
telemt_desync_frames_bucket_total{bucket="1_2"} 5663
telemt_desync_frames_bucket_total{bucket="3_10"} 9153
telemt_desync_frames_bucket_total{bucket="gt_10"} 8768
telemt_pool_swap_total 129
telemt_pool_force_close_total 3825
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 391
telemt_me_draining_writers_reap_progress_total 38597
telemt_me_writer_removed_unexpected_total 883
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3195
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 36228
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3607
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 218
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 34772
telemt_me_writer_teardown_success_total{mode="normal"} 39423
telemt_me_writer_teardown_noop_total 38603
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 74525
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 76180
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 76801
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 77404
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 77821
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 78006
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 78026
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 78026
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 78026
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 78026
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 78026
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 78026
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 78026
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 49.676258
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 78026
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 391
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 808
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 65
telemt_user_connections_total{user="hello"} 4995382
telemt_user_connections_current{user="hello"} 2004
telemt_user_octets_from_client{user="hello"} 146003782373 (135.98 GB)
telemt_user_octets_to_client{user="hello"} 2387723273087 (2.17 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 830
telemt_user_unique_ips_recent_window{user="hello"} 707
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 118077.1 (32h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6626702
telemt_connections_bad_total 560449
telemt_connections_current 2970
telemt_connections_me_current 2970
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 220638
telemt_upstream_connect_attempt_total 54425
telemt_upstream_connect_success_total 53882
telemt_upstream_connect_fail_total 143
telemt_upstream_connect_attempts_per_request{bucket="1"} 54025
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26914
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25036
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 740
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1192
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 143
telemt_me_keepalive_timeout_total 72
telemt_me_reconnect_attempts_total 2442
telemt_me_reconnect_success_total 1068
telemt_me_reader_eof_total 1006
telemt_me_idle_close_by_peer_total 1006
telemt_me_route_drop_no_conn_total 2335984
telemt_me_route_drop_channel_closed_total 141
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4931390
telemt_me_endpoint_quarantine_total 845
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 878
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 42
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
telemt_desync_total 23461
telemt_desync_full_logged_total 7955
telemt_desync_suppressed_total 15506
telemt_desync_frames_bucket_total{bucket="1_2"} 5703
telemt_desync_frames_bucket_total{bucket="3_10"} 8991
telemt_desync_frames_bucket_total{bucket="gt_10"} 8767
telemt_pool_swap_total 127
telemt_pool_force_close_total 3663
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 414
telemt_me_draining_writers_reap_progress_total 39647
telemt_me_writer_removed_unexpected_total 995
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3410
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 37253
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3425
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 238
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 35984
telemt_me_writer_teardown_success_total{mode="normal"} 40663
telemt_me_writer_teardown_noop_total 39659
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 77437
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 78943
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 79439
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 79979
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 80234
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 80289
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 80322
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 80322
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 80322
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 80322
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 80322
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 80322
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 80322
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 33.976350
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 80322
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 414
telemt_me_refill_failed_total 76
telemt_me_writer_restored_same_endpoint_total 934
telemt_me_writer_restored_fallback_total 5
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 56
telemt_user_connections_total{user="hello"} 4925918
telemt_user_connections_current{user="hello"} 2970
telemt_user_octets_from_client{user="hello"} 137211223323 (127.79 GB)
telemt_user_octets_to_client{user="hello"} 2253520370791 (2.05 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 1237
telemt_user_unique_ips_recent_window{user="hello"} 584
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 118124.0 (32h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21190088
telemt_connections_bad_total 1794235
telemt_connections_current 814
telemt_connections_direct_current 809
telemt_connections_me_current 5
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 645295
telemt_upstream_connect_attempt_total 207139
telemt_upstream_connect_success_total 188425
telemt_upstream_connect_fail_total 16607
telemt_upstream_connect_attempts_per_request{bucket="1"} 205032
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 132032
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 45855
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1573
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8965
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16607
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 65449
telemt_me_reconnect_success_total 2493
telemt_me_reader_eof_total 1582
telemt_me_idle_close_by_peer_total 1581
telemt_me_route_drop_no_conn_total 40058505
telemt_me_route_drop_channel_closed_total 130
telemt_me_route_drop_queue_full_total 13
telemt_me_route_drop_queue_full_profile_total{profile="high"} 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 17026209
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 919
telemt_me_single_endpoint_outage_enter_total 153
telemt_me_single_endpoint_outage_exit_total 145
telemt_me_single_endpoint_outage_reconnect_attempt_total 318
telemt_me_single_endpoint_outage_reconnect_success_total 77
telemt_me_single_endpoint_quarantine_bypass_total 318
telemt_me_single_endpoint_shadow_rotate_total 927
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 69
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 41
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_desync_total 33008
telemt_desync_full_logged_total 9954
telemt_desync_suppressed_total 23054
telemt_desync_frames_bucket_total{bucket="1_2"} 7196
telemt_desync_frames_bucket_total{bucket="3_10"} 14649
telemt_desync_frames_bucket_total{bucket="gt_10"} 11163
telemt_pool_swap_total 122
telemt_pool_force_close_total 3916
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 866
telemt_me_draining_writers_reap_progress_total 37225
telemt_me_writer_removed_unexpected_total 2361
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5055
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 34279
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 24
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3358
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 558
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 33309
telemt_me_writer_teardown_success_total{mode="normal"} 39334
telemt_me_writer_teardown_noop_total 37252
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 69466
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 72088
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 73436
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 75179
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 76140
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 76482
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 76567
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 76569
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 76572
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 76577
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 76577
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 76581
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 76586
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 218.328173
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 76586
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 866
telemt_me_refill_failed_total 3813
telemt_me_writer_restored_same_endpoint_total 1710
telemt_me_writer_restored_fallback_total 22
telemt_me_no_writer_failfast_total 666
telemt_me_async_recovery_trigger_total 14678
telemt_me_writer_removed_unexpected_minus_restored_total 629
telemt_user_connections_total{user="hello"} 17162364
telemt_user_connections_current{user="hello"} 814
telemt_user_octets_from_client{user="hello"} 251119623013 (233.87 GB)
telemt_user_octets_to_client{user="hello"} 1325330172514 (1.21 TB)
telemt_user_msgs_from_client{user="hello"} 401554
telemt_user_msgs_to_client{user="hello"} 790079
telemt_user_unique_ips_current{user="hello"} 408
telemt_user_unique_ips_recent_window{user="hello"} 427
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 118084.0 (32h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6400874
telemt_connections_bad_total 610438
telemt_connections_current 2731
telemt_connections_me_current 2731
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 135349
telemt_upstream_connect_attempt_total 62972
telemt_upstream_connect_success_total 62240
telemt_upstream_connect_fail_total 626
telemt_upstream_connect_attempts_per_request{bucket="1"} 62866
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35871
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26007
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 361
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 626
telemt_me_reconnect_attempts_total 69914
telemt_me_reconnect_success_total 1885
telemt_me_reader_eof_total 1657
telemt_me_idle_close_by_peer_total 1656
telemt_me_route_drop_no_conn_total 2470558
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4977083
telemt_me_endpoint_quarantine_total 804
telemt_me_single_endpoint_outage_enter_total 24
telemt_me_single_endpoint_outage_exit_total 24
telemt_me_single_endpoint_outage_reconnect_attempt_total 25
telemt_me_single_endpoint_outage_reconnect_success_total 24
telemt_me_single_endpoint_quarantine_bypass_total 25
telemt_me_single_endpoint_shadow_rotate_total 898
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
telemt_me_writers_active_current 42
telemt_desync_total 24817
telemt_desync_full_logged_total 8700
telemt_desync_suppressed_total 16117
telemt_desync_frames_bucket_total{bucket="1_2"} 4898
telemt_desync_frames_bucket_total{bucket="3_10"} 9579
telemt_desync_frames_bucket_total{bucket="gt_10"} 10340
telemt_pool_swap_total 123
telemt_pool_force_close_total 3490
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 414
telemt_me_draining_writers_reap_progress_total 41720
telemt_me_writer_removed_unexpected_total 1693
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4218
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 39227
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3084
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 406
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 38230
telemt_me_writer_teardown_success_total{mode="normal"} 43445
telemt_me_writer_teardown_noop_total 41721
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 83804
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 84680
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 84972
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 85134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 85163
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 85166
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 85166
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 85166
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 85166
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 85166
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 85166
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 85166
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 85166
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.954625
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 85166
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 414
telemt_me_refill_failed_total 4214
telemt_me_writer_restored_same_endpoint_total 1573
telemt_me_writer_restored_fallback_total 38
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7313
telemt_me_writer_removed_unexpected_minus_restored_total 82
telemt_user_connections_total{user="hello"} 4969194
telemt_user_connections_current{user="hello"} 2731
telemt_user_octets_from_client{user="hello"} 129306707448 (120.43 GB)
telemt_user_octets_to_client{user="hello"} 2064233089982 (1.88 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 1205
telemt_user_unique_ips_recent_window{user="hello"} 339
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 54919.7 (15h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4402730
telemt_connections_bad_total 183313
telemt_connections_current 2359
telemt_connections_me_current 2359
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 1741878
telemt_upstream_connect_attempt_total 31758
telemt_upstream_connect_success_total 31547
telemt_upstream_connect_fail_total 204
telemt_upstream_connect_attempts_per_request{bucket="1"} 31751
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19198
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12266
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 83
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 204
telemt_me_reconnect_attempts_total 46080
telemt_me_reconnect_success_total 1031
telemt_me_reader_eof_total 720
telemt_me_idle_close_by_peer_total 720
telemt_me_route_drop_no_conn_total 1109353
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2178217
telemt_me_endpoint_quarantine_total 392
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 50
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 50
telemt_me_single_endpoint_shadow_rotate_total 424
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
telemt_desync_total 11810
telemt_desync_full_logged_total 4044
telemt_desync_suppressed_total 7766
telemt_desync_frames_bucket_total{bucket="1_2"} 2279
telemt_desync_frames_bucket_total{bucket="3_10"} 4521
telemt_desync_frames_bucket_total{bucket="gt_10"} 5010
telemt_pool_swap_total 59
telemt_pool_force_close_total 1730
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 153
telemt_me_draining_writers_reap_progress_total 20399
telemt_me_writer_removed_unexpected_total 791
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1746
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19473
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1521
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 209
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18669
telemt_me_writer_teardown_success_total{mode="normal"} 21219
telemt_me_writer_teardown_noop_total 20401
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 41058
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 41357
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 41514
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 41620
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 41620
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 41620
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 41620
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 41620
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 41620
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 41620
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 41620
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 41620
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 41620
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.696557
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 41620
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 153
telemt_me_refill_failed_total 2617
telemt_me_writer_restored_same_endpoint_total 919
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4264
telemt_user_connections_total{user="hello"} 2180640
telemt_user_connections_current{user="hello"} 2359
telemt_user_octets_from_client{user="hello"} 58245887652 (54.25 GB)
telemt_user_octets_to_client{user="hello"} 955400570714 (889.79 GB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 1075
telemt_user_unique_ips_recent_window{user="hello"} 303
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 35890.6 (9h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 254476
telemt_connections_bad_total 1932
telemt_connections_current 539
telemt_connections_me_current 539
telemt_handshake_timeouts_total 6603
telemt_upstream_connect_attempt_total 17322
telemt_upstream_connect_success_total 17279
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 17318
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7269
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9914
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_reconnect_attempts_total 413
telemt_me_reconnect_success_total 235
telemt_me_reader_eof_total 235
telemt_me_idle_close_by_peer_total 235
telemt_me_route_drop_no_conn_total 71275
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 226831
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
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 46
telemt_desync_total 1213
telemt_desync_full_logged_total 331
telemt_desync_suppressed_total 882
telemt_desync_frames_bucket_total{bucket="1_2"} 425
telemt_desync_frames_bucket_total{bucket="3_10"} 465
telemt_desync_frames_bucket_total{bucket="gt_10"} 323
telemt_pool_swap_total 39
telemt_pool_force_close_total 868
telemt_me_writer_close_signal_drop_total 34
telemt_me_draining_writers_reap_progress_total 15688
telemt_me_writer_removed_unexpected_total 224
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 989
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14934
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 866
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14820
telemt_me_writer_teardown_success_total{mode="normal"} 15923
telemt_me_writer_teardown_noop_total 15688
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 31349
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 31583
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 31601
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 31611
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 31611
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 31611
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 31611
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 31611
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 31611
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 31611
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 31611
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 31611
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 31611
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.251494
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 31611
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 34
telemt_me_refill_failed_total 10
telemt_me_writer_restored_same_endpoint_total 203
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 226471
telemt_user_connections_current{user="hello"} 539
telemt_user_octets_from_client{user="hello"} 3798461620 (3.54 GB)
telemt_user_octets_to_client{user="hello"} 140147509920 (130.52 GB)
telemt_user_unique_ips_current{user="hello"} 219
telemt_user_unique_ips_recent_window{user="hello"} 80
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 118088.5 (32h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7754681
telemt_connections_bad_total 771198
telemt_connections_current 1739
telemt_connections_me_current 1739
telemt_handshake_timeouts_total 220857
telemt_upstream_connect_attempt_total 46590
telemt_upstream_connect_success_total 46420
telemt_upstream_connect_fail_total 133
telemt_upstream_connect_attempts_per_request{bucket="1"} 46553
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22959
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23420
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 133
telemt_me_reconnect_attempts_total 1690
telemt_me_reconnect_success_total 906
telemt_me_reader_eof_total 900
telemt_me_idle_close_by_peer_total 900
telemt_me_route_drop_no_conn_total 2202760
telemt_me_route_drop_channel_closed_total 52
telemt_me_route_drop_queue_full_total 23
telemt_me_route_drop_queue_full_profile_total{profile="high"} 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5782571
telemt_me_endpoint_quarantine_total 846
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 905
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
telemt_me_writers_active_current 43
telemt_desync_total 22624
telemt_desync_full_logged_total 7460
telemt_desync_suppressed_total 15164
telemt_desync_frames_bucket_total{bucket="1_2"} 5667
telemt_desync_frames_bucket_total{bucket="3_10"} 8214
telemt_desync_frames_bucket_total{bucket="gt_10"} 8743
telemt_pool_swap_total 131
telemt_pool_force_close_total 3491
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 411
telemt_me_draining_writers_reap_progress_total 42066
telemt_me_writer_removed_unexpected_total 863
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3283
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 39673
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3403
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 38575
telemt_me_writer_teardown_success_total{mode="normal"} 42956
telemt_me_writer_teardown_noop_total 42068
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 83599
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 84544
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 84731
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 84936
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 85024
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 85024
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 85024
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 85024
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 85024
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 85024
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 85024
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 85024
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 85024
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 11.003994
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 85024
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 411
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 811
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 44
telemt_user_connections_total{user="hello"} 5757127
telemt_user_connections_current{user="hello"} 1737
telemt_user_octets_from_client{user="hello"} 113845444624 (106.03 GB)
telemt_user_octets_to_client{user="hello"} 2694469668300 (2.45 TB)
telemt_user_unique_ips_current{user="hello"} 639
telemt_user_unique_ips_recent_window{user="hello"} 488
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 118085.0 (32h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6739340
telemt_connections_bad_total 659485
telemt_connections_current 3240
telemt_connections_me_current 3240
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 182567
telemt_upstream_connect_attempt_total 62432
telemt_upstream_connect_success_total 61963
telemt_upstream_connect_fail_total 409
telemt_upstream_connect_attempts_per_request{bucket="1"} 62372
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35801
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25028
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 616
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 409
telemt_me_reconnect_attempts_total 5790
telemt_me_reconnect_success_total 1276
telemt_me_reader_eof_total 1146
telemt_me_idle_close_by_peer_total 1146
telemt_me_seq_mismatch_total 55
telemt_me_route_drop_no_conn_total 2257988
telemt_me_route_drop_channel_closed_total 191
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5150495
telemt_me_endpoint_quarantine_total 936
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 29
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 29
telemt_me_single_endpoint_shadow_rotate_total 906
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
telemt_me_writers_active_current 42
telemt_desync_total 21472
telemt_desync_full_logged_total 7145
telemt_desync_suppressed_total 14327
telemt_desync_frames_bucket_total{bucket="1_2"} 5405
telemt_desync_frames_bucket_total{bucket="3_10"} 7856
telemt_desync_frames_bucket_total{bucket="gt_10"} 8211
telemt_pool_swap_total 129
telemt_pool_force_close_total 3410
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 411
telemt_me_draining_writers_reap_progress_total 40603
telemt_me_writer_removed_unexpected_total 1159
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3838
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 37981
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3187
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 223
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 37193
telemt_me_writer_teardown_success_total{mode="normal"} 41819
telemt_me_writer_teardown_noop_total 40607
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 80691
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 81792
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 82191
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 82388
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 82426
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 82426
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 82426
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 82426
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 82426
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 82426
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 82426
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 82426
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 82426
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 11.609848
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 82426
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 411
telemt_me_refill_failed_total 260
telemt_me_writer_restored_same_endpoint_total 998
telemt_me_writer_restored_fallback_total 73
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 82
telemt_me_writer_removed_unexpected_minus_restored_total 88
telemt_user_connections_total{user="hello"} 5153145
telemt_user_connections_current{user="hello"} 3240
telemt_user_octets_from_client{user="hello"} 96630842485 (89.99 GB)
telemt_user_octets_to_client{user="hello"} 2227068387320 (2.03 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1291
telemt_user_unique_ips_recent_window{user="hello"} 419
```