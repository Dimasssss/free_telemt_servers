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

# Server Metrics 2026-03-22 04:38:26 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 27121.0 (7h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 440052
telemt_connections_bad_total 29420
telemt_connections_current 1149
telemt_connections_me_current 1149
telemt_handshake_timeouts_total 24484
telemt_upstream_connect_attempt_total 11322
telemt_upstream_connect_success_total 11321
telemt_upstream_connect_attempts_per_request{bucket="1"} 11321
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4006
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7289
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 15
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_reconnect_attempts_total 306
telemt_me_reconnect_success_total 177
telemt_me_reader_eof_total 173
telemt_me_idle_close_by_peer_total 173
telemt_me_route_drop_no_conn_total 91203
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 363016
telemt_me_endpoint_quarantine_total 220
telemt_me_single_endpoint_shadow_rotate_total 226
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 4
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
telemt_desync_total 3285
telemt_desync_full_logged_total 893
telemt_desync_suppressed_total 2392
telemt_desync_frames_bucket_total{bucket="1_2"} 1143
telemt_desync_frames_bucket_total{bucket="3_10"} 1249
telemt_desync_frames_bucket_total{bucket="gt_10"} 893
telemt_pool_swap_total 30
telemt_pool_force_close_total 765
telemt_me_writer_close_signal_drop_total 59
telemt_me_draining_writers_reap_progress_total 10208
telemt_me_writer_removed_unexpected_total 171
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 690
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 9681
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 760
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 9443
telemt_me_writer_teardown_success_total{mode="normal"} 10371
telemt_me_writer_teardown_noop_total 10209
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 19916
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 20253
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 20397
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 20502
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 20562
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 20580
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 20580
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 20580
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 20580
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 20580
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 20580
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 20580
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 20580
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.298355
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 20580
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 59
telemt_me_refill_failed_total 7
telemt_me_writer_restored_same_endpoint_total 160
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 362105
telemt_user_connections_current{user="hello"} 1149
telemt_user_octets_from_client{user="hello"} 4940721812 (4.60 GB)
telemt_user_octets_to_client{user="hello"} 126861176792 (118.15 GB)
telemt_user_unique_ips_current{user="hello"} 466
telemt_user_unique_ips_recent_window{user="hello"} 159
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 40487.0 (11h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 892765
telemt_connections_bad_total 61273
telemt_connections_current 1038
telemt_connections_me_current 1038
telemt_handshake_timeouts_total 31548
telemt_upstream_connect_attempt_total 18964
telemt_upstream_connect_success_total 18670
telemt_upstream_connect_fail_total 262
telemt_upstream_connect_attempts_per_request{bucket="1"} 18932
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8229
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10394
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 47
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 262
telemt_me_reconnect_attempts_total 1533
telemt_me_reconnect_success_total 578
telemt_me_reader_eof_total 515
telemt_me_idle_close_by_peer_total 515
telemt_me_route_drop_no_conn_total 359827
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 706243
telemt_me_endpoint_quarantine_total 372
telemt_me_single_endpoint_outage_enter_total 20
telemt_me_single_endpoint_outage_exit_total 20
telemt_me_single_endpoint_outage_reconnect_attempt_total 20
telemt_me_single_endpoint_outage_reconnect_success_total 20
telemt_me_single_endpoint_quarantine_bypass_total 20
telemt_me_single_endpoint_shadow_rotate_total 326
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
telemt_me_writers_active_current 45
telemt_desync_total 2999
telemt_desync_full_logged_total 1724
telemt_desync_suppressed_total 1275
telemt_desync_frames_bucket_total{bucket="1_2"} 631
telemt_desync_frames_bucket_total{bucket="3_10"} 1154
telemt_desync_frames_bucket_total{bucket="gt_10"} 1214
telemt_pool_swap_total 43
telemt_pool_force_close_total 1149
telemt_me_writer_close_signal_drop_total 82
telemt_me_draining_writers_reap_progress_total 16805
telemt_me_writer_removed_unexpected_total 491
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1395
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15912
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1127
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 22
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15656
telemt_me_writer_teardown_success_total{mode="normal"} 17307
telemt_me_writer_teardown_noop_total 16805
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 33539
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 33875
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 33999
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 34098
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 34110
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 34112
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 34112
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 34112
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 34112
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 34112
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 34112
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 34112
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 34112
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.066765
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 34112
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 82
telemt_me_refill_failed_total 50
telemt_me_writer_restored_same_endpoint_total 435
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 44
telemt_user_connections_total{user="hello"} 705142
telemt_user_connections_current{user="hello"} 1038
telemt_user_octets_from_client{user="hello"} 11290965564 (10.52 GB)
telemt_user_octets_to_client{user="hello"} 254941993656 (237.43 GB)
telemt_user_unique_ips_current{user="hello"} 655
telemt_user_unique_ips_recent_window{user="hello"} 239
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 115346.9 (32h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8049276
telemt_connections_bad_total 686362
telemt_connections_current 2857
telemt_connections_me_current 2857
telemt_handshake_timeouts_total 264266
telemt_upstream_connect_attempt_total 43072
telemt_upstream_connect_success_total 42994
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 43002
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19461
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23349
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 178
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1635
telemt_me_reconnect_success_total 851
telemt_me_reader_eof_total 860
telemt_me_idle_close_by_peer_total 860
telemt_me_route_drop_no_conn_total 4588782
telemt_me_route_drop_channel_closed_total 66
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6482965
telemt_me_endpoint_quarantine_total 744
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 865
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
telemt_me_writers_active_current 43
telemt_desync_total 27207
telemt_desync_full_logged_total 9047
telemt_desync_suppressed_total 18160
telemt_desync_frames_bucket_total{bucket="1_2"} 5881
telemt_desync_frames_bucket_total{bucket="3_10"} 10637
telemt_desync_frames_bucket_total{bucket="gt_10"} 10689
telemt_pool_swap_total 125
telemt_pool_force_close_total 4075
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 619
telemt_me_draining_writers_reap_progress_total 39279
telemt_me_writer_removed_unexpected_total 828
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3257
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 36385
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3834
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 241
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 35204
telemt_me_writer_teardown_success_total{mode="normal"} 39642
telemt_me_writer_teardown_noop_total 39323
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 72529
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 74432
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 75458
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 77014
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 78087
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 78664
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 78954
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 78965
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 78965
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 78965
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 78965
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 78965
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 78965
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 164.470906
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 78965
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 619
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 759
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 64
telemt_user_connections_total{user="hello"} 6474684
telemt_user_connections_current{user="hello"} 2857
telemt_user_octets_from_client{user="hello"} 109914123792 (102.37 GB)
telemt_user_octets_to_client{user="hello"} 2180792715224 (1.98 TB)
telemt_user_unique_ips_current{user="hello"} 1267
telemt_user_unique_ips_recent_window{user="hello"} 317
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 115348.3 (32h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6643531
telemt_connections_bad_total 596461
telemt_connections_current 2518
telemt_connections_me_current 2518
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 220578
telemt_upstream_connect_attempt_total 47003
telemt_upstream_connect_success_total 46605
telemt_upstream_connect_fail_total 201
telemt_upstream_connect_attempts_per_request{bucket="1"} 46806
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23057
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22957
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 558
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 201
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 2035
telemt_me_reconnect_success_total 913
telemt_me_reader_eof_total 888
telemt_me_idle_close_by_peer_total 888
telemt_me_route_drop_no_conn_total 2300268
telemt_me_route_drop_channel_closed_total 284
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4960842
telemt_me_endpoint_quarantine_total 732
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 890
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
telemt_desync_total 23113
telemt_desync_full_logged_total 7903
telemt_desync_suppressed_total 15210
telemt_desync_frames_bucket_total{bucket="1_2"} 5554
telemt_desync_frames_bucket_total{bucket="3_10"} 8978
telemt_desync_frames_bucket_total{bucket="gt_10"} 8581
telemt_pool_swap_total 126
telemt_pool_force_close_total 3706
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 375
telemt_me_draining_writers_reap_progress_total 37713
telemt_me_writer_removed_unexpected_total 869
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3110
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 35413
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3489
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 217
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 34007
telemt_me_writer_teardown_success_total{mode="normal"} 38523
telemt_me_writer_teardown_noop_total 37719
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 72867
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 74452
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 75038
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 75624
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 76037
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 76222
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 76242
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 76242
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 76242
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 76242
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 76242
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 76242
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 76242
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 48.819995
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 76242
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 375
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 795
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 64
telemt_user_connections_total{user="hello"} 4882499
telemt_user_connections_current{user="hello"} 2518
telemt_user_octets_from_client{user="hello"} 143789147313 (133.91 GB)
telemt_user_octets_to_client{user="hello"} 2329522020263 (2.12 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1111
telemt_user_unique_ips_recent_window{user="hello"} 298
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 115316.0 (32h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6500902
telemt_connections_bad_total 554817
telemt_connections_current 1916
telemt_connections_me_current 1916
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 214868
telemt_upstream_connect_attempt_total 53436
telemt_upstream_connect_success_total 52934
telemt_upstream_connect_fail_total 142
telemt_upstream_connect_attempts_per_request{bucket="1"} 53076
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26593
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24519
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 664
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1158
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 142
telemt_me_keepalive_timeout_total 62
telemt_me_reconnect_attempts_total 2353
telemt_me_reconnect_success_total 1026
telemt_me_reader_eof_total 969
telemt_me_idle_close_by_peer_total 969
telemt_me_route_drop_no_conn_total 2256930
telemt_me_route_drop_channel_closed_total 132
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4831637
telemt_me_endpoint_quarantine_total 820
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 857
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
telemt_me_writers_active_current 44
telemt_desync_total 23001
telemt_desync_full_logged_total 7785
telemt_desync_suppressed_total 15216
telemt_desync_frames_bucket_total{bucket="1_2"} 5624
telemt_desync_frames_bucket_total{bucket="3_10"} 8819
telemt_desync_frames_bucket_total{bucket="gt_10"} 8558
telemt_pool_swap_total 124
telemt_pool_force_close_total 3579
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 406
telemt_me_draining_writers_reap_progress_total 38861
telemt_me_writer_removed_unexpected_total 956
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3300
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 36535
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3345
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 234
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 35282
telemt_me_writer_teardown_success_total{mode="normal"} 39835
telemt_me_writer_teardown_noop_total 38873
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 75926
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 77391
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 77874
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 78392
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 78630
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 78675
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 78708
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 78708
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 78708
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 78708
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 78708
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 78708
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 78708
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 32.316720
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 78708
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 406
telemt_me_refill_failed_total 74
telemt_me_writer_restored_same_endpoint_total 899
telemt_me_writer_restored_fallback_total 5
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 52
telemt_user_connections_total{user="hello"} 4826497
telemt_user_connections_current{user="hello"} 1916
telemt_user_octets_from_client{user="hello"} 135958357187 (126.62 GB)
telemt_user_octets_to_client{user="hello"} 2209157271543 (2.01 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 899
telemt_user_unique_ips_recent_window{user="hello"} 224
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 115351.7 (32h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20851457
telemt_connections_bad_total 1742488
telemt_connections_current 3198
telemt_connections_me_current 3198
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 631969
telemt_upstream_connect_attempt_total 203821
telemt_upstream_connect_success_total 185518
telemt_upstream_connect_fail_total 16473
telemt_upstream_connect_attempts_per_request{bucket="1"} 201991
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 130558
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 44785
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1224
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8951
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16473
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 65189
telemt_me_reconnect_success_total 2440
telemt_me_reader_eof_total 1526
telemt_me_idle_close_by_peer_total 1525
telemt_me_route_drop_no_conn_total 39640190
telemt_me_route_drop_channel_closed_total 128
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16772940
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 891
telemt_me_single_endpoint_outage_enter_total 144
telemt_me_single_endpoint_outage_exit_total 144
telemt_me_single_endpoint_outage_reconnect_attempt_total 297
telemt_me_single_endpoint_outage_reconnect_success_total 76
telemt_me_single_endpoint_quarantine_bypass_total 297
telemt_me_single_endpoint_shadow_rotate_total 905
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
telemt_me_writers_active_current 60
telemt_me_writers_warm_current 27
telemt_desync_total 32546
telemt_desync_full_logged_total 9796
telemt_desync_suppressed_total 22750
telemt_desync_frames_bucket_total{bucket="1_2"} 7070
telemt_desync_frames_bucket_total{bucket="3_10"} 14434
telemt_desync_frames_bucket_total{bucket="gt_10"} 11042
telemt_pool_swap_total 119
telemt_pool_force_close_total 3836
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 836
telemt_me_draining_writers_reap_progress_total 36148
telemt_me_writer_removed_unexpected_total 2265
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4864
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 33294
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 24
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3302
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 534
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 32312
telemt_me_writer_teardown_success_total{mode="normal"} 38158
telemt_me_writer_teardown_noop_total 36175
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 67305
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 69879
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 71206
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 72935
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 73889
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 74231
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 74314
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 74316
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 74319
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 74324
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 74324
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 74328
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 74333
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 217.271405
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 74333
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 836
telemt_me_refill_failed_total 3809
telemt_me_writer_restored_same_endpoint_total 1663
telemt_me_writer_restored_fallback_total 21
telemt_me_no_writer_failfast_total 666
telemt_me_async_recovery_trigger_total 14678
telemt_me_writer_removed_unexpected_minus_restored_total 581
telemt_user_connections_total{user="hello"} 16907639
telemt_user_connections_current{user="hello"} 3198
telemt_user_octets_from_client{user="hello"} 242178126168 (225.55 GB)
telemt_user_octets_to_client{user="hello"} 1289213134131 (1.17 TB)
telemt_user_msgs_from_client{user="hello"} 398569
telemt_user_msgs_to_client{user="hello"} 788102
telemt_user_unique_ips_current{user="hello"} 1402
telemt_user_unique_ips_recent_window{user="hello"} 393
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 115319.1 (32h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6275331
telemt_connections_bad_total 604776
telemt_connections_current 2295
telemt_connections_me_current 2295
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 132299
telemt_upstream_connect_attempt_total 61877
telemt_upstream_connect_success_total 61175
telemt_upstream_connect_fail_total 599
telemt_upstream_connect_attempts_per_request{bucket="1"} 61774
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35387
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25430
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 357
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 599
telemt_me_reconnect_attempts_total 69838
telemt_me_reconnect_success_total 1843
telemt_me_reader_eof_total 1626
telemt_me_idle_close_by_peer_total 1625
telemt_me_route_drop_no_conn_total 2432590
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4869811
telemt_me_endpoint_quarantine_total 779
telemt_me_single_endpoint_outage_enter_total 23
telemt_me_single_endpoint_outage_exit_total 23
telemt_me_single_endpoint_outage_reconnect_attempt_total 24
telemt_me_single_endpoint_outage_reconnect_success_total 23
telemt_me_single_endpoint_quarantine_bypass_total 24
telemt_me_single_endpoint_shadow_rotate_total 874
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
telemt_me_writers_active_current 46
telemt_me_writers_warm_current 38
telemt_desync_total 24312
telemt_desync_full_logged_total 8519
telemt_desync_suppressed_total 15793
telemt_desync_frames_bucket_total{bucket="1_2"} 4770
telemt_desync_frames_bucket_total{bucket="3_10"} 9404
telemt_desync_frames_bucket_total{bucket="gt_10"} 10138
telemt_pool_swap_total 119
telemt_pool_force_close_total 3401
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 407
telemt_me_draining_writers_reap_progress_total 40749
telemt_me_writer_removed_unexpected_total 1662
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4126
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 38317
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3000
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 401
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 37348
telemt_me_writer_teardown_success_total{mode="normal"} 42443
telemt_me_writer_teardown_noop_total 40750
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 81874
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 82731
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 83023
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 83161
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 83190
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 83193
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 83193
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 83193
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 83193
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 83193
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 83193
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 83193
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 83193
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.561242
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 83193
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 407
telemt_me_refill_failed_total 4213
telemt_me_writer_restored_same_endpoint_total 1547
telemt_me_writer_restored_fallback_total 35
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7305
telemt_me_writer_removed_unexpected_minus_restored_total 80
telemt_user_connections_total{user="hello"} 4862187
telemt_user_connections_current{user="hello"} 2295
telemt_user_octets_from_client{user="hello"} 127441723620 (118.69 GB)
telemt_user_octets_to_client{user="hello"} 2008120724370 (1.83 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 1051
telemt_user_unique_ips_recent_window{user="hello"} 283
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 52155.1 (14h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4228435
telemt_connections_bad_total 179004
telemt_connections_current 1842
telemt_connections_me_current 1842
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 1685026
telemt_upstream_connect_attempt_total 30727
telemt_upstream_connect_success_total 30526
telemt_upstream_connect_fail_total 194
telemt_upstream_connect_attempts_per_request{bucket="1"} 30720
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18701
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11742
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 83
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 194
telemt_me_reconnect_attempts_total 45979
telemt_me_reconnect_success_total 1015
telemt_me_reader_eof_total 702
telemt_me_idle_close_by_peer_total 702
telemt_me_route_drop_no_conn_total 1058758
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2077739
telemt_me_endpoint_quarantine_total 379
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 50
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 50
telemt_me_single_endpoint_shadow_rotate_total 403
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
telemt_desync_total 11163
telemt_desync_full_logged_total 3862
telemt_desync_suppressed_total 7301
telemt_desync_frames_bucket_total{bucket="1_2"} 2102
telemt_desync_frames_bucket_total{bucket="3_10"} 4273
telemt_desync_frames_bucket_total{bucket="gt_10"} 4788
telemt_pool_swap_total 56
telemt_pool_force_close_total 1647
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 149
telemt_me_draining_writers_reap_progress_total 19466
telemt_me_writer_removed_unexpected_total 774
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1685
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18583
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1440
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 207
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17819
telemt_me_writer_teardown_success_total{mode="normal"} 20268
telemt_me_writer_teardown_noop_total 19468
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 39205
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 39491
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 39630
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 39736
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 39736
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 39736
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 39736
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 39736
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 39736
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 39736
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 39736
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 39736
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 39736
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.519302
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 39736
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 149
telemt_me_refill_failed_total 2612
telemt_me_writer_restored_same_endpoint_total 908
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4264
telemt_user_connections_total{user="hello"} 2081106
telemt_user_connections_current{user="hello"} 1842
telemt_user_octets_from_client{user="hello"} 56737608600 (52.84 GB)
telemt_user_octets_to_client{user="hello"} 901759687418 (839.83 GB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 925
telemt_user_unique_ips_recent_window{user="hello"} 259
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 33126.1 (9h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 233308
telemt_connections_bad_total 1865
telemt_connections_current 447
telemt_connections_me_current 447
telemt_handshake_timeouts_total 6082
telemt_upstream_connect_attempt_total 16048
telemt_upstream_connect_success_total 16010
telemt_upstream_connect_fail_total 36
telemt_upstream_connect_attempts_per_request{bucket="1"} 16046
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6750
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9176
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 84
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 36
telemt_me_reconnect_attempts_total 386
telemt_me_reconnect_success_total 209
telemt_me_reader_eof_total 215
telemt_me_idle_close_by_peer_total 215
telemt_me_route_drop_no_conn_total 65038
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 207165
telemt_me_endpoint_quarantine_total 320
telemt_me_single_endpoint_shadow_rotate_total 287
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
telemt_me_writers_active_current 44
telemt_desync_total 1177
telemt_desync_full_logged_total 317
telemt_desync_suppressed_total 860
telemt_desync_frames_bucket_total{bucket="1_2"} 418
telemt_desync_frames_bucket_total{bucket="3_10"} 452
telemt_desync_frames_bucket_total{bucket="gt_10"} 307
telemt_pool_swap_total 36
telemt_pool_force_close_total 803
telemt_me_writer_close_signal_drop_total 29
telemt_me_draining_writers_reap_progress_total 14526
telemt_me_writer_removed_unexpected_total 206
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 920
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13821
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 801
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13723
telemt_me_writer_teardown_success_total{mode="normal"} 14741
telemt_me_writer_teardown_noop_total 14526
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 29027
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 29239
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 29257
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 29267
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 29267
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 29267
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 29267
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 29267
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 29267
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 29267
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 29267
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 29267
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 29267
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.175821
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 29267
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 29
telemt_me_refill_failed_total 10
telemt_me_writer_restored_same_endpoint_total 188
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 17
telemt_user_connections_total{user="hello"} 206810
telemt_user_connections_current{user="hello"} 447
telemt_user_octets_from_client{user="hello"} 3525751444 (3.28 GB)
telemt_user_octets_to_client{user="hello"} 128142962404 (119.34 GB)
telemt_user_unique_ips_current{user="hello"} 198
telemt_user_unique_ips_recent_window{user="hello"} 56
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 115323.5 (32h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7610098
telemt_connections_bad_total 763436
telemt_connections_current 2454
telemt_connections_me_current 2454
telemt_handshake_timeouts_total 216650
telemt_upstream_connect_attempt_total 45511
telemt_upstream_connect_success_total 45345
telemt_upstream_connect_fail_total 129
telemt_upstream_connect_attempts_per_request{bucket="1"} 45474
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22450
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22854
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 129
telemt_me_reconnect_attempts_total 1671
telemt_me_reconnect_success_total 890
telemt_me_reader_eof_total 881
telemt_me_idle_close_by_peer_total 881
telemt_me_route_drop_no_conn_total 2169489
telemt_me_route_drop_channel_closed_total 52
telemt_me_route_drop_queue_full_total 23
telemt_me_route_drop_queue_full_profile_total{profile="high"} 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5665569
telemt_me_endpoint_quarantine_total 831
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 885
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
telemt_me_writers_active_current 44
telemt_desync_total 22141
telemt_desync_full_logged_total 7284
telemt_desync_suppressed_total 14857
telemt_desync_frames_bucket_total{bucket="1_2"} 5546
telemt_desync_frames_bucket_total{bucket="3_10"} 8045
telemt_desync_frames_bucket_total{bucket="gt_10"} 8550
telemt_pool_swap_total 128
telemt_pool_force_close_total 3390
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 400
telemt_me_draining_writers_reap_progress_total 41059
telemt_me_writer_removed_unexpected_total 846
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3196
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 38734
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3302
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 37669
telemt_me_writer_teardown_success_total{mode="normal"} 41930
telemt_me_writer_teardown_noop_total 41061
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 81613
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 82524
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 82703
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 82903
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 82991
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 82991
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 82991
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 82991
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 82991
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 82991
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 82991
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 82991
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 82991
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.746388
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 82991
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 400
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 795
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 5640338
telemt_user_connections_current{user="hello"} 2454
telemt_user_octets_from_client{user="hello"} 112198148444 (104.49 GB)
telemt_user_octets_to_client{user="hello"} 2629424764012 (2.39 TB)
telemt_user_unique_ips_current{user="hello"} 1044
telemt_user_unique_ips_recent_window{user="hello"} 276
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 115320.2 (32h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6595635
telemt_connections_bad_total 646943
telemt_connections_current 2493
telemt_connections_me_current 2493
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 178652
telemt_upstream_connect_attempt_total 61356
telemt_upstream_connect_success_total 60891
telemt_upstream_connect_fail_total 405
telemt_upstream_connect_attempts_per_request{bucket="1"} 61296
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35266
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24491
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 616
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 405
telemt_me_reconnect_attempts_total 5753
telemt_me_reconnect_success_total 1257
telemt_me_reader_eof_total 1129
telemt_me_idle_close_by_peer_total 1129
telemt_me_seq_mismatch_total 52
telemt_me_route_drop_no_conn_total 2223535
telemt_me_route_drop_channel_closed_total 191
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5035026
telemt_me_endpoint_quarantine_total 910
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 29
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 29
telemt_me_single_endpoint_shadow_rotate_total 883
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
telemt_desync_total 20853
telemt_desync_full_logged_total 6966
telemt_desync_suppressed_total 13887
telemt_desync_frames_bucket_total{bucket="1_2"} 5307
telemt_desync_frames_bucket_total{bucket="3_10"} 7630
telemt_desync_frames_bucket_total{bucket="gt_10"} 7916
telemt_pool_swap_total 126
telemt_pool_force_close_total 3338
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 395
telemt_me_draining_writers_reap_progress_total 39627
telemt_me_writer_removed_unexpected_total 1140
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3749
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 37074
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3115
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 223
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 36289
telemt_me_writer_teardown_success_total{mode="normal"} 40823
telemt_me_writer_teardown_noop_total 39631
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 78761
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 79839
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 80220
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 80416
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 80454
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 80454
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 80454
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 80454
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 80454
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 80454
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 80454
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 80454
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 80454
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 11.404800
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 80454
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 395
telemt_me_refill_failed_total 259
telemt_me_writer_restored_same_endpoint_total 983
telemt_me_writer_restored_fallback_total 70
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 82
telemt_me_writer_removed_unexpected_minus_restored_total 87
telemt_user_connections_total{user="hello"} 5037831
telemt_user_connections_current{user="hello"} 2493
telemt_user_octets_from_client{user="hello"} 95009301713 (88.48 GB)
telemt_user_octets_to_client{user="hello"} 2163391234084 (1.97 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1057
telemt_user_unique_ips_recent_window{user="hello"} 279
```