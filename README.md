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

# Server Metrics 2026-03-22 10:56:34 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 49811.9 (13h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1357185
telemt_connections_bad_total 69882
telemt_connections_current 1904
telemt_connections_me_current 1904
telemt_handshake_timeouts_total 61923
telemt_upstream_connect_attempt_total 19208
telemt_upstream_connect_success_total 19207
telemt_upstream_connect_attempts_per_request{bucket="1"} 19207
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6628
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12520
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 48
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 643
telemt_me_reconnect_success_total 313
telemt_me_reader_eof_total 309
telemt_me_idle_close_by_peer_total 309
telemt_me_route_drop_no_conn_total 756449
telemt_me_route_drop_channel_closed_total 369
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1137443
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_endpoint_quarantine_total 354
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 403
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
telemt_me_writers_active_current 45
telemt_desync_total 7357
telemt_desync_full_logged_total 2172
telemt_desync_suppressed_total 5185
telemt_desync_frames_bucket_total{bucket="1_2"} 2134
telemt_desync_frames_bucket_total{bucket="3_10"} 2780
telemt_desync_frames_bucket_total{bucket="gt_10"} 2443
telemt_pool_swap_total 55
telemt_pool_force_close_total 1601
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 226
telemt_me_draining_writers_reap_progress_total 17488
telemt_me_writer_removed_unexpected_total 304
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1230
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16482
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1566
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 35
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15887
telemt_me_writer_teardown_success_total{mode="normal"} 17712
telemt_me_writer_teardown_noop_total 17490
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 30940
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 31904
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 32674
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 33885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 34722
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 35114
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 35202
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 35202
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 35202
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 35202
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 35202
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 35202
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 35202
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 98.116976
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 35202
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 226
telemt_me_refill_failed_total 17
telemt_me_writer_restored_same_endpoint_total 281
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 1135351
telemt_user_connections_current{user="hello"} 1904
telemt_user_octets_from_client{user="hello"} 18370256116 (17.11 GB)
telemt_user_octets_to_client{user="hello"} 355965744476 (331.52 GB)
telemt_user_unique_ips_current{user="hello"} 632
telemt_user_unique_ips_recent_window{user="hello"} 277
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 63177.7 (17h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2175991
telemt_connections_bad_total 178850
telemt_connections_current 1131
telemt_connections_direct_current 1131
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 51766
telemt_upstream_connect_attempt_total 42727
telemt_upstream_connect_success_total 42222
telemt_upstream_connect_fail_total 440
telemt_upstream_connect_attempts_per_request{bucket="1"} 42662
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26022
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16096
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 104
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 440
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 3287
telemt_me_reconnect_success_total 1440
telemt_me_reader_eof_total 1325
telemt_me_idle_close_by_peer_total 1325
telemt_me_route_drop_no_conn_total 1670504
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1706273
telemt_me_endpoint_quarantine_total 549
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 29
telemt_me_single_endpoint_outage_reconnect_success_total 29
telemt_me_single_endpoint_quarantine_bypass_total 29
telemt_me_single_endpoint_shadow_rotate_total 501
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
telemt_me_writers_active_current 37
telemt_desync_total 7009
telemt_desync_full_logged_total 3968
telemt_desync_suppressed_total 3041
telemt_desync_frames_bucket_total{bucket="1_2"} 1596
telemt_desync_frames_bucket_total{bucket="3_10"} 2752
telemt_desync_frames_bucket_total{bucket="gt_10"} 2661
telemt_pool_swap_total 64
telemt_pool_force_close_total 1787
telemt_me_writer_close_signal_drop_total 148
telemt_me_draining_writers_reap_progress_total 25362
telemt_me_writer_removed_unexpected_total 1289
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2797
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 23850
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1599
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 188
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 23575
telemt_me_writer_teardown_success_total{mode="normal"} 26647
telemt_me_writer_teardown_noop_total 25362
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 50910
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 51577
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 51791
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 51989
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 52007
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 52009
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 52009
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 52009
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 52009
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 52009
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 52009
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 52009
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 52009
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.600064
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 52009
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 148
telemt_me_refill_failed_total 83
telemt_me_writer_restored_same_endpoint_total 1194
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 21
telemt_me_writer_removed_unexpected_minus_restored_total 73
telemt_user_connections_total{user="hello"} 1718036
telemt_user_connections_current{user="hello"} 1131
telemt_user_octets_from_client{user="hello"} 23024202726 (21.44 GB)
telemt_user_octets_to_client{user="hello"} 462524298121 (430.76 GB)
telemt_user_msgs_from_client{user="hello"} 42063
telemt_user_msgs_to_client{user="hello"} 167511
telemt_user_unique_ips_current{user="hello"} 654
telemt_user_unique_ips_recent_window{user="hello"} 720
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 138038.7 (38h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11642756
telemt_connections_bad_total 988290
telemt_connections_current 4850
telemt_connections_me_current 4850
telemt_handshake_timeouts_total 314623
telemt_upstream_connect_attempt_total 50352
telemt_upstream_connect_success_total 50272
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 50280
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22741
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27319
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 206
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2160
telemt_me_reconnect_success_total 1103
telemt_me_reader_eof_total 1085
telemt_me_idle_close_by_peer_total 1084
telemt_me_route_drop_no_conn_total 8644718
telemt_me_route_drop_channel_closed_total 101
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9285903
telemt_me_endpoint_quarantine_total 883
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 1028
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
telemt_me_writers_active_current 43
telemt_desync_total 38489
telemt_desync_full_logged_total 12424
telemt_desync_suppressed_total 26065
telemt_desync_frames_bucket_total{bucket="1_2"} 8652
telemt_desync_frames_bucket_total{bucket="3_10"} 15015
telemt_desync_frames_bucket_total{bucket="gt_10"} 14822
telemt_pool_swap_total 149
telemt_pool_force_close_total 5001
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 780
telemt_me_draining_writers_reap_progress_total 45927
telemt_me_writer_removed_unexpected_total 1045
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3935
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 42461
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4667
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 334
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 40926
telemt_me_writer_teardown_success_total{mode="normal"} 46396
telemt_me_writer_teardown_noop_total 45971
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 84160
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 86746
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 88048
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 89915
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 91234
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 91961
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 92355
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 92367
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 92367
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 92367
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 92367
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 92367
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 92367
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 210.038073
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 92367
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 780
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 960
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 78
telemt_user_connections_total{user="hello"} 9275105
telemt_user_connections_current{user="hello"} 4850
telemt_user_octets_from_client{user="hello"} 142464412496 (132.68 GB)
telemt_user_octets_to_client{user="hello"} 2730858199256 (2.48 TB)
telemt_user_unique_ips_current{user="hello"} 1800
telemt_user_unique_ips_recent_window{user="hello"} 879
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 138039.1 (38h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9014077
telemt_connections_bad_total 808002
telemt_connections_current 4854
telemt_connections_me_current 4854
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 275315
telemt_upstream_connect_attempt_total 56821
telemt_upstream_connect_success_total 56249
telemt_upstream_connect_fail_total 263
telemt_upstream_connect_attempts_per_request{bucket="1"} 56512
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27349
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27608
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 130
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1162
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 263
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 182
telemt_me_reconnect_attempts_total 3133
telemt_me_reconnect_success_total 1284
telemt_me_reader_eof_total 1174
telemt_me_idle_close_by_peer_total 1174
telemt_me_route_drop_no_conn_total 3642947
telemt_me_route_drop_channel_closed_total 372
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6714958
telemt_me_endpoint_quarantine_total 871
telemt_me_single_endpoint_outage_enter_total 20
telemt_me_single_endpoint_outage_exit_total 20
telemt_me_single_endpoint_outage_reconnect_attempt_total 25
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 25
telemt_me_single_endpoint_shadow_rotate_total 1058
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
telemt_me_writers_active_current 87
telemt_desync_total 30410
telemt_desync_full_logged_total 10286
telemt_desync_suppressed_total 20124
telemt_desync_frames_bucket_total{bucket="1_2"} 7410
telemt_desync_frames_bucket_total{bucket="3_10"} 11728
telemt_desync_frames_bucket_total{bucket="gt_10"} 11272
telemt_pool_swap_total 148
telemt_pool_force_close_total 4513
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 511
telemt_me_draining_writers_reap_progress_total 44349
telemt_me_writer_removed_unexpected_total 1209
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3903
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 41549
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4182
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 331
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 39836
telemt_me_writer_teardown_success_total{mode="normal"} 45452
telemt_me_writer_teardown_noop_total 44355
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 84999
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 87303
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 88144
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 88968
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 89539
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 89787
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 89807
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 89807
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 89807
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 89807
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 89807
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 89807
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 89807
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 66.186298
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 89807
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 511
telemt_me_refill_failed_total 101
telemt_me_writer_restored_same_endpoint_total 1102
telemt_me_writer_restored_fallback_total 12
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 212
telemt_me_writer_removed_unexpected_minus_restored_total 95
telemt_user_connections_total{user="hello"} 6636581
telemt_user_connections_current{user="hello"} 4854
telemt_user_octets_from_client{user="hello"} 173864896435 (161.92 GB)
telemt_user_octets_to_client{user="hello"} 3058508827186 (2.78 TB)
telemt_user_msgs_from_client{user="hello"} 42822
telemt_user_msgs_to_client{user="hello"} 51589
telemt_user_unique_ips_current{user="hello"} 1973
telemt_user_unique_ips_recent_window{user="hello"} 586
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 138004.3 (38h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8549505
telemt_connections_bad_total 710558
telemt_connections_current 3784
telemt_connections_me_current 3784
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 274958
telemt_upstream_connect_attempt_total 61078
telemt_upstream_connect_success_total 60372
telemt_upstream_connect_fail_total 147
telemt_upstream_connect_attempts_per_request{bucket="1"} 60519
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29513
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28473
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1003
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1383
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 147
telemt_me_keepalive_timeout_total 238
telemt_me_reconnect_attempts_total 3661
telemt_me_reconnect_success_total 1493
telemt_me_reader_eof_total 1382
telemt_me_idle_close_by_peer_total 1382
telemt_me_route_drop_no_conn_total 3609448
telemt_me_route_drop_channel_closed_total 240
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6419516
telemt_me_endpoint_quarantine_total 951
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 19
telemt_me_single_endpoint_outage_reconnect_success_total 15
telemt_me_single_endpoint_quarantine_bypass_total 19
telemt_me_single_endpoint_shadow_rotate_total 1012
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
telemt_me_writers_active_current 42
telemt_desync_total 29607
telemt_desync_full_logged_total 10083
telemt_desync_suppressed_total 19524
telemt_desync_frames_bucket_total{bucket="1_2"} 7142
telemt_desync_frames_bucket_total{bucket="3_10"} 11425
telemt_desync_frames_bucket_total{bucket="gt_10"} 11040
telemt_pool_swap_total 146
telemt_pool_force_close_total 4462
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 528
telemt_me_draining_writers_reap_progress_total 45158
telemt_me_writer_removed_unexpected_total 1407
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4254
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 42249
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 17
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4061
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 401
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 40696
telemt_me_writer_teardown_success_total{mode="normal"} 46503
telemt_me_writer_teardown_noop_total 45175
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 87522
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 89557
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 90298
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 91096
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 91489
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 91615
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 91674
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 91676
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 91678
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 91678
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 91678
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 91678
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 91678
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 55.918638
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 91678
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 528
telemt_me_refill_failed_total 112
telemt_me_writer_restored_same_endpoint_total 1312
telemt_me_writer_restored_fallback_total 7
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 50
telemt_me_writer_removed_unexpected_minus_restored_total 88
telemt_user_connections_total{user="hello"} 6410931
telemt_user_connections_current{user="hello"} 3784
telemt_user_octets_from_client{user="hello"} 158662906779 (147.77 GB)
telemt_user_octets_to_client{user="hello"} 2784026989871 (2.53 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 1406
telemt_user_unique_ips_recent_window{user="hello"} 664
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 8282.9 (2h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3539010
telemt_connections_bad_total 236369
telemt_connections_current 6960
telemt_connections_me_current 6960
telemt_handshake_timeouts_total 53445
telemt_upstream_connect_attempt_total 9549
telemt_upstream_connect_success_total 9045
telemt_upstream_connect_fail_total 348
telemt_upstream_connect_attempts_per_request{bucket="1"} 9393
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4263
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2061
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2719
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 348
telemt_me_keepalive_timeout_total 397
telemt_me_reconnect_attempts_total 568
telemt_me_reconnect_success_total 238
telemt_me_reader_eof_total 165
telemt_me_idle_close_by_peer_total 165
telemt_me_route_drop_no_conn_total 8085324
telemt_me_route_drop_channel_closed_total 15
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2951726
telemt_me_endpoint_quarantine_total 60
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 25
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 25
telemt_me_single_endpoint_shadow_rotate_total 66
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 8
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
telemt_me_writers_active_current 45
telemt_desync_total 4298
telemt_desync_full_logged_total 1137
telemt_desync_suppressed_total 3161
telemt_desync_frames_bucket_total{bucket="1_2"} 775
telemt_desync_frames_bucket_total{bucket="3_10"} 1683
telemt_desync_frames_bucket_total{bucket="gt_10"} 1840
telemt_pool_swap_total 7
telemt_pool_force_close_total 279
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 108
telemt_me_draining_writers_reap_progress_total 2177
telemt_me_writer_removed_unexpected_total 208
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 376
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 1992
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 164
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 115
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 1898
telemt_me_writer_teardown_success_total{mode="normal"} 2368
telemt_me_writer_teardown_noop_total 2179
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 3757
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 4140
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 4312
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 4480
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 4533
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 4546
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 4547
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 4547
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 4547
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 4547
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 4547
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 4547
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 4547
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.944385
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 4547
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 108
telemt_me_refill_failed_total 12
telemt_me_writer_restored_same_endpoint_total 168
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 50
telemt_me_writer_removed_unexpected_minus_restored_total 37
telemt_user_connections_total{user="hello"} 2955537
telemt_user_connections_current{user="hello"} 6960
telemt_user_octets_from_client{user="hello"} 15264158318 (14.22 GB)
telemt_user_octets_to_client{user="hello"} 88133019059 (82.08 GB)
telemt_user_msgs_from_client{user="hello"} 6014
telemt_user_msgs_to_client{user="hello"} 4995
telemt_user_unique_ips_current{user="hello"} 2487
telemt_user_unique_ips_recent_window{user="hello"} 1396
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 138009.9 (38h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8249765
telemt_connections_bad_total 717392
telemt_connections_current 3759
telemt_connections_me_current 3759
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 169663
telemt_upstream_connect_attempt_total 86390
telemt_upstream_connect_success_total 85532
telemt_upstream_connect_fail_total 738
telemt_upstream_connect_attempts_per_request{bucket="1"} 86270
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 53602
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30480
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 208
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1242
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 738
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 70659
telemt_me_reconnect_success_total 2185
telemt_me_reader_eof_total 1921
telemt_me_idle_close_by_peer_total 1920
telemt_me_route_drop_no_conn_total 3639486
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 45
telemt_me_route_drop_queue_full_profile_total{profile="high"} 45
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6515743
telemt_me_endpoint_quarantine_total 925
telemt_me_single_endpoint_outage_enter_total 28
telemt_me_single_endpoint_outage_exit_total 28
telemt_me_single_endpoint_outage_reconnect_attempt_total 30
telemt_me_single_endpoint_outage_reconnect_success_total 28
telemt_me_single_endpoint_quarantine_bypass_total 30
telemt_me_single_endpoint_shadow_rotate_total 1038
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
telemt_desync_total 33027
telemt_desync_full_logged_total 11384
telemt_desync_suppressed_total 21643
telemt_desync_frames_bucket_total{bucket="1_2"} 6761
telemt_desync_frames_bucket_total{bucket="3_10"} 12675
telemt_desync_frames_bucket_total{bucket="gt_10"} 13591
telemt_pool_swap_total 143
telemt_pool_force_close_total 4158
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 502
telemt_me_draining_writers_reap_progress_total 47534
telemt_me_writer_removed_unexpected_total 1950
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4912
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 44597
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3626
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 532
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 43376
telemt_me_writer_teardown_success_total{mode="normal"} 49509
telemt_me_writer_teardown_noop_total 47535
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 95400
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 96449
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 96762
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 97003
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 97034
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 97037
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 97037
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 97040
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 97044
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 97044
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 97044
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 97044
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 97044
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.559542
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 97044
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 502
telemt_me_refill_failed_total 4234
telemt_me_writer_restored_same_endpoint_total 1816
telemt_me_writer_restored_fallback_total 41
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7333
telemt_me_writer_removed_unexpected_minus_restored_total 93
telemt_user_connections_total{user="hello"} 6519121
telemt_user_connections_current{user="hello"} 3759
telemt_user_octets_from_client{user="hello"} 157043738319 (146.26 GB)
telemt_user_octets_to_client{user="hello"} 2580973084733 (2.35 TB)
telemt_user_msgs_from_client{user="hello"} 146235
telemt_user_msgs_to_client{user="hello"} 572261
telemt_user_unique_ips_current{user="hello"} 1461
telemt_user_unique_ips_recent_window{user="hello"} 658
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 74845.9 (20h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7323009
telemt_connections_bad_total 275907
telemt_connections_current 4974
telemt_connections_me_current 4974
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 3005539
telemt_upstream_connect_attempt_total 38917
telemt_upstream_connect_success_total 38634
telemt_upstream_connect_fail_total 276
telemt_upstream_connect_attempts_per_request{bucket="1"} 38910
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22521
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16009
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 104
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 276
telemt_me_reconnect_attempts_total 47696
telemt_me_reconnect_success_total 1334
telemt_me_reader_eof_total 998
telemt_me_idle_close_by_peer_total 998
telemt_me_route_drop_no_conn_total 2242050
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3613613
telemt_me_endpoint_quarantine_total 512
telemt_me_single_endpoint_outage_enter_total 17
telemt_me_single_endpoint_outage_exit_total 17
telemt_me_single_endpoint_outage_reconnect_attempt_total 57
telemt_me_single_endpoint_outage_reconnect_success_total 17
telemt_me_single_endpoint_quarantine_bypass_total 57
telemt_me_single_endpoint_shadow_rotate_total 568
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 18
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
telemt_desync_total 19582
telemt_desync_full_logged_total 6586
telemt_desync_suppressed_total 12996
telemt_desync_frames_bucket_total{bucket="1_2"} 3973
telemt_desync_frames_bucket_total{bucket="3_10"} 7529
telemt_desync_frames_bucket_total{bucket="gt_10"} 8080
telemt_pool_swap_total 79
telemt_pool_force_close_total 2396
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 234
telemt_me_draining_writers_reap_progress_total 26641
telemt_me_writer_removed_unexpected_total 1066
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2378
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 25354
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2041
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 355
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 24245
telemt_me_writer_teardown_success_total{mode="normal"} 27732
telemt_me_writer_teardown_noop_total 26647
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 53572
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 54026
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 54233
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 54379
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 54379
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 54379
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 54379
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 54379
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 54379
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 54379
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 54379
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 54379
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 54379
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.229475
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 54379
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 234
telemt_me_refill_failed_total 2695
telemt_me_writer_restored_same_endpoint_total 1189
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4328
telemt_user_connections_total{user="hello"} 3612589
telemt_user_connections_current{user="hello"} 4974
telemt_user_octets_from_client{user="hello"} 85790341896 (79.90 GB)
telemt_user_octets_to_client{user="hello"} 1472625104466 (1.34 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 1992
telemt_user_unique_ips_recent_window{user="hello"} 598
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 55816.5 (15h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 577177
telemt_connections_bad_total 4306
telemt_connections_current 936
telemt_connections_me_current 936
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 10592
telemt_upstream_connect_attempt_total 29219
telemt_upstream_connect_success_total 29152
telemt_upstream_connect_fail_total 60
telemt_upstream_connect_attempts_per_request{bucket="1"} 29212
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13541
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15305
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 306
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 60
telemt_me_reconnect_attempts_total 1211
telemt_me_reconnect_success_total 517
telemt_me_reader_eof_total 514
telemt_me_idle_close_by_peer_total 514
telemt_me_route_drop_no_conn_total 189512
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 522868
telemt_me_endpoint_quarantine_total 498
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 471
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
telemt_me_writers_active_current 43
telemt_desync_total 2785
telemt_desync_full_logged_total 792
telemt_desync_suppressed_total 1993
telemt_desync_frames_bucket_total{bucket="1_2"} 761
telemt_desync_frames_bucket_total{bucket="3_10"} 1080
telemt_desync_frames_bucket_total{bucket="gt_10"} 944
telemt_pool_swap_total 58
telemt_pool_force_close_total 1408
telemt_me_writer_close_signal_drop_total 73
telemt_me_draining_writers_reap_progress_total 23769
telemt_me_writer_removed_unexpected_total 498
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1756
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22528
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1332
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 76
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22361
telemt_me_writer_teardown_success_total{mode="normal"} 24284
telemt_me_writer_teardown_noop_total 23769
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 47588
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 47931
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 48028
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 48053
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 48053
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 48053
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 48053
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 48053
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 48053
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 48053
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 48053
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 48053
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 48053
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.567361
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 48053
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 73
telemt_me_refill_failed_total 40
telemt_me_writer_restored_same_endpoint_total 463
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 524803
telemt_user_connections_current{user="hello"} 936
telemt_user_octets_from_client{user="hello"} 10120168193 (9.43 GB)
telemt_user_octets_to_client{user="hello"} 248173907611 (231.13 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 342
telemt_user_unique_ips_recent_window{user="hello"} 156
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 138014.1 (38h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10028326
telemt_connections_bad_total 1173269
telemt_connections_current 5587
telemt_connections_me_current 5587
telemt_handshake_timeouts_total 267001
telemt_upstream_connect_attempt_total 52915
telemt_upstream_connect_success_total 52712
telemt_upstream_connect_fail_total 156
telemt_upstream_connect_attempts_per_request{bucket="1"} 52868
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26040
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26631
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 156
telemt_me_reconnect_attempts_total 2047
telemt_me_reconnect_success_total 1095
telemt_me_reader_eof_total 1059
telemt_me_idle_close_by_peer_total 1059
telemt_me_route_drop_no_conn_total 2888310
telemt_me_route_drop_channel_closed_total 74
telemt_me_route_drop_queue_full_total 29
telemt_me_route_drop_queue_full_profile_total{profile="high"} 29
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7475206
telemt_me_endpoint_quarantine_total 975
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 12
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 12
telemt_me_single_endpoint_shadow_rotate_total 1042
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
telemt_desync_total 30347
telemt_desync_full_logged_total 9961
telemt_desync_suppressed_total 20386
telemt_desync_frames_bucket_total{bucket="1_2"} 7430
telemt_desync_frames_bucket_total{bucket="3_10"} 11106
telemt_desync_frames_bucket_total{bucket="gt_10"} 11811
telemt_pool_swap_total 153
telemt_pool_force_close_total 4149
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 503
telemt_me_draining_writers_reap_progress_total 47714
telemt_me_writer_removed_unexpected_total 1018
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3859
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 44905
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4029
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 120
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 43565
telemt_me_writer_teardown_success_total{mode="normal"} 48764
telemt_me_writer_teardown_noop_total 47716
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 94698
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 95919
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 96142
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 96380
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 96477
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 96480
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 96480
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 96480
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 96480
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 96480
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 96480
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 96480
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 96480
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 13.357952
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 96480
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 503
telemt_me_refill_failed_total 49
telemt_me_writer_restored_same_endpoint_total 955
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 52
telemt_user_connections_total{user="hello"} 7446960
telemt_user_connections_current{user="hello"} 5587
telemt_user_octets_from_client{user="hello"} 144342253856 (134.43 GB)
telemt_user_octets_to_client{user="hello"} 3460003545716 (3.15 TB)
telemt_user_unique_ips_current{user="hello"} 1988
telemt_user_unique_ips_recent_window{user="hello"} 763
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 138011.1 (38h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8724041
telemt_connections_bad_total 988128
telemt_connections_current 4761
telemt_connections_me_current 4761
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 223546
telemt_upstream_connect_attempt_total 77411
telemt_upstream_connect_success_total 76858
telemt_upstream_connect_fail_total 483
telemt_upstream_connect_attempts_per_request{bucket="1"} 77341
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 42888
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31092
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 909
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1969
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 483
telemt_me_reconnect_attempts_total 6627
telemt_me_reconnect_success_total 1562
telemt_me_reader_eof_total 1385
telemt_me_idle_close_by_peer_total 1385
telemt_me_seq_mismatch_total 66
telemt_me_route_drop_no_conn_total 3162082
telemt_me_route_drop_channel_closed_total 273
telemt_me_route_drop_queue_full_total 15
telemt_me_route_drop_queue_full_profile_total{profile="high"} 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6668189
telemt_me_endpoint_quarantine_total 1075
telemt_me_single_endpoint_outage_enter_total 35
telemt_me_single_endpoint_outage_exit_total 35
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 33
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1046
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
telemt_me_writers_active_current 43
telemt_desync_total 29616
telemt_desync_full_logged_total 9757
telemt_desync_suppressed_total 19859
telemt_desync_frames_bucket_total{bucket="1_2"} 7309
telemt_desync_frames_bucket_total{bucket="3_10"} 10959
telemt_desync_frames_bucket_total{bucket="gt_10"} 11348
telemt_pool_swap_total 150
telemt_pool_force_close_total 4082
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 507
telemt_me_draining_writers_reap_progress_total 46397
telemt_me_writer_removed_unexpected_total 1403
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4519
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 43345
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3780
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 302
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 42315
telemt_me_writer_teardown_success_total{mode="normal"} 47864
telemt_me_writer_teardown_noop_total 46401
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 92171
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 93514
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 93972
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 94227
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 94265
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 94265
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 94265
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 94265
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 94265
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 94265
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 94265
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 94265
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 94265
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 13.777298
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 94265
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 507
telemt_me_refill_failed_total 291
telemt_me_writer_restored_same_endpoint_total 1215
telemt_me_writer_restored_fallback_total 90
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 128
telemt_me_writer_removed_unexpected_minus_restored_total 98
telemt_user_connections_total{user="hello"} 6676142
telemt_user_connections_current{user="hello"} 4761
telemt_user_octets_from_client{user="hello"} 120585395993 (112.30 GB)
telemt_user_octets_to_client{user="hello"} 2793711196619 (2.54 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 1843
telemt_user_unique_ips_recent_window{user="hello"} 660
```