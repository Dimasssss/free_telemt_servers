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

# Server Metrics 2026-03-22 07:47:47 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 38484.6 (10h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 826484
telemt_connections_bad_total 51440
telemt_connections_current 1550
telemt_connections_me_current 1550
telemt_handshake_timeouts_total 39591
telemt_upstream_connect_attempt_total 15492
telemt_upstream_connect_success_total 15491
telemt_upstream_connect_attempts_per_request{bucket="1"} 15491
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5365
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10078
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 37
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_failed_total 1
telemt_me_reconnect_attempts_total 430
telemt_me_reconnect_success_total 241
telemt_me_reader_eof_total 239
telemt_me_idle_close_by_peer_total 239
telemt_me_route_drop_no_conn_total 319250
telemt_me_route_drop_channel_closed_total 120
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 684606
telemt_me_endpoint_quarantine_total 276
telemt_me_single_endpoint_shadow_rotate_total 313
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 7
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
telemt_desync_total 5423
telemt_desync_full_logged_total 1529
telemt_desync_suppressed_total 3894
telemt_desync_frames_bucket_total{bucket="1_2"} 1713
telemt_desync_frames_bucket_total{bucket="3_10"} 2028
telemt_desync_frames_bucket_total{bucket="gt_10"} 1682
telemt_pool_swap_total 42
telemt_pool_force_close_total 1171
telemt_me_writer_close_signal_drop_total 122
telemt_me_draining_writers_reap_progress_total 14074
telemt_me_writer_removed_unexpected_total 236
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 974
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13290
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1151
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 20
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 12903
telemt_me_writer_teardown_success_total{mode="normal"} 14264
telemt_me_writer_teardown_noop_total 14075
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 26384
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 26943
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 27324
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 27843
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 28182
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 28317
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 28339
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 28339
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 28339
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 28339
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 28339
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 28339
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 28339
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 37.278533
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 28339
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 122
telemt_me_refill_failed_total 10
telemt_me_writer_restored_same_endpoint_total 221
telemt_me_writer_removed_unexpected_minus_restored_total 15
telemt_user_connections_total{user="hello"} 683380
telemt_user_connections_current{user="hello"} 1550
telemt_user_octets_from_client{user="hello"} 9300010204 (8.66 GB)
telemt_user_octets_to_client{user="hello"} 233123378084 (217.11 GB)
telemt_user_unique_ips_current{user="hello"} 591
telemt_user_unique_ips_recent_window{user="hello"} 271
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 51850.5 (14h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1312188
telemt_connections_bad_total 126524
telemt_connections_current 1212
telemt_connections_me_current 1212
telemt_handshake_timeouts_total 40257
telemt_upstream_connect_attempt_total 27088
telemt_upstream_connect_success_total 26684
telemt_upstream_connect_fail_total 352
telemt_upstream_connect_attempts_per_request{bucket="1"} 27036
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13541
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13084
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 352
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 1992
telemt_me_reconnect_success_total 821
telemt_me_reader_eof_total 710
telemt_me_idle_close_by_peer_total 710
telemt_me_route_drop_no_conn_total 509664
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 988067
telemt_me_endpoint_quarantine_total 477
telemt_me_single_endpoint_outage_enter_total 23
telemt_me_single_endpoint_outage_exit_total 23
telemt_me_single_endpoint_outage_reconnect_attempt_total 23
telemt_me_single_endpoint_outage_reconnect_success_total 23
telemt_me_single_endpoint_quarantine_bypass_total 23
telemt_me_single_endpoint_shadow_rotate_total 415
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 26
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
telemt_desync_total 4280
telemt_desync_full_logged_total 2504
telemt_desync_suppressed_total 1776
telemt_desync_frames_bucket_total{bucket="1_2"} 913
telemt_desync_frames_bucket_total{bucket="3_10"} 1657
telemt_desync_frames_bucket_total{bucket="gt_10"} 1710
telemt_pool_swap_total 55
telemt_pool_force_close_total 1480
telemt_me_writer_close_signal_drop_total 121
telemt_me_draining_writers_reap_progress_total 21199
telemt_me_writer_removed_unexpected_total 682
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1890
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19978
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1407
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 73
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19719
telemt_me_writer_teardown_success_total{mode="normal"} 21868
telemt_me_writer_teardown_noop_total 21199
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 42202
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 42720
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 42905
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 43053
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 43065
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 43067
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 43067
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 43067
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 43067
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 43067
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 43067
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 43067
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 43067
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.851975
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 43067
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 121
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 623
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 19
telemt_me_writer_removed_unexpected_minus_restored_total 40
telemt_user_connections_total{user="hello"} 989730
telemt_user_connections_current{user="hello"} 1212
telemt_user_octets_from_client{user="hello"} 15569691326 (14.50 GB)
telemt_user_octets_to_client{user="hello"} 357032223559 (332.51 GB)
telemt_user_msgs_from_client{user="hello"} 6406
telemt_user_msgs_to_client{user="hello"} 10605
telemt_user_unique_ips_current{user="hello"} 779
telemt_user_unique_ips_recent_window{user="hello"} 431
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 126710.5 (35h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9238871
telemt_connections_bad_total 843773
telemt_connections_current 4257
telemt_connections_me_current 4257
telemt_handshake_timeouts_total 284791
telemt_upstream_connect_attempt_total 46721
telemt_upstream_connect_success_total 46641
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 46649
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21048
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25398
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 189
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1817
telemt_me_reconnect_success_total 927
telemt_me_reader_eof_total 930
telemt_me_idle_close_by_peer_total 930
telemt_me_route_drop_no_conn_total 5028101
telemt_me_route_drop_channel_closed_total 77
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7263716
telemt_me_endpoint_quarantine_total 798
telemt_me_single_endpoint_outage_enter_total 6
telemt_me_single_endpoint_outage_exit_total 6
telemt_me_single_endpoint_outage_reconnect_attempt_total 6
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 6
telemt_me_single_endpoint_shadow_rotate_total 950
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
telemt_me_writers_active_current 42
telemt_desync_total 31535
telemt_desync_full_logged_total 10413
telemt_desync_suppressed_total 21122
telemt_desync_frames_bucket_total{bucket="1_2"} 6863
telemt_desync_frames_bucket_total{bucket="3_10"} 12232
telemt_desync_frames_bucket_total{bucket="gt_10"} 12440
telemt_pool_swap_total 137
telemt_pool_force_close_total 4521
telemt_pool_stale_pick_total 18
telemt_me_writer_close_signal_drop_total 682
telemt_me_draining_writers_reap_progress_total 42654
telemt_me_writer_removed_unexpected_total 894
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3542
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 39496
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4245
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 276
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 38133
telemt_me_writer_teardown_success_total{mode="normal"} 43038
telemt_me_writer_teardown_noop_total 42698
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 78624
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 80760
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 81907
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 83591
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 84775
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 85404
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 85725
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 85736
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 85736
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 85736
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 85736
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 85736
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 85736
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 180.686540
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 85736
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 682
telemt_me_refill_failed_total 47
telemt_me_writer_restored_same_endpoint_total 825
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 64
telemt_user_connections_total{user="hello"} 7254206
telemt_user_connections_current{user="hello"} 4257
telemt_user_octets_from_client{user="hello"} 121594434008 (113.24 GB)
telemt_user_octets_to_client{user="hello"} 2464333316404 (2.24 TB)
telemt_user_unique_ips_current{user="hello"} 1677
telemt_user_unique_ips_recent_window{user="hello"} 604
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 126712.0 (35h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7591968
telemt_connections_bad_total 674214
telemt_connections_current 3131
telemt_connections_me_current 3131
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 247593
telemt_upstream_connect_attempt_total 52456
telemt_upstream_connect_success_total 51995
telemt_upstream_connect_fail_total 240
telemt_upstream_connect_attempts_per_request{bucket="1"} 52235
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25133
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25642
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 107
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1113
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 240
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 2741
telemt_me_reconnect_success_total 1039
telemt_me_reader_eof_total 963
telemt_me_idle_close_by_peer_total 963
telemt_me_route_drop_no_conn_total 2546975
telemt_me_route_drop_channel_closed_total 309
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5627165
telemt_me_endpoint_quarantine_total 805
telemt_me_single_endpoint_outage_enter_total 17
telemt_me_single_endpoint_outage_exit_total 17
telemt_me_single_endpoint_outage_reconnect_attempt_total 20
telemt_me_single_endpoint_outage_reconnect_success_total 16
telemt_me_single_endpoint_quarantine_bypass_total 20
telemt_me_single_endpoint_shadow_rotate_total 980
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
telemt_me_writers_active_current 43
telemt_desync_total 25864
telemt_desync_full_logged_total 8860
telemt_desync_suppressed_total 17004
telemt_desync_frames_bucket_total{bucket="1_2"} 6183
telemt_desync_frames_bucket_total{bucket="3_10"} 10026
telemt_desync_frames_bucket_total{bucket="gt_10"} 9655
telemt_pool_swap_total 138
telemt_pool_force_close_total 4136
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 431
telemt_me_draining_writers_reap_progress_total 41076
telemt_me_writer_removed_unexpected_total 984
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3459
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 38520
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3895
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 241
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 36940
telemt_me_writer_teardown_success_total{mode="normal"} 41979
telemt_me_writer_teardown_noop_total 41082
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 79098
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 80968
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 81672
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 82359
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 82836
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 83041
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 83061
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 83061
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 83061
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 83061
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 83061
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 83061
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 83061
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 55.574112
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 83061
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 431
telemt_me_refill_failed_total 94
telemt_me_writer_restored_same_endpoint_total 883
telemt_me_writer_restored_fallback_total 10
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 206
telemt_me_writer_removed_unexpected_minus_restored_total 91
telemt_user_connections_total{user="hello"} 5549592
telemt_user_connections_current{user="hello"} 3131
telemt_user_octets_from_client{user="hello"} 156447473712 (145.70 GB)
telemt_user_octets_to_client{user="hello"} 2677187513572 (2.43 TB)
telemt_user_msgs_from_client{user="hello"} 41825
telemt_user_msgs_to_client{user="hello"} 50380
telemt_user_unique_ips_current{user="hello"} 1113
telemt_user_unique_ips_recent_window{user="hello"} 557
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 126676.7 (35h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7345066
telemt_connections_bad_total 606106
telemt_connections_current 4484
telemt_connections_me_current 4484
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 243418
telemt_upstream_connect_attempt_total 57344
telemt_upstream_connect_success_total 56675
telemt_upstream_connect_fail_total 147
telemt_upstream_connect_attempts_per_request{bucket="1"} 56822
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27917
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26565
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 899
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1294
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 147
telemt_me_keepalive_timeout_total 237
telemt_me_reconnect_attempts_total 2738
telemt_me_reconnect_success_total 1190
telemt_me_reader_eof_total 1098
telemt_me_idle_close_by_peer_total 1098
telemt_me_route_drop_no_conn_total 2964257
telemt_me_route_drop_channel_closed_total 173
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5476256
telemt_me_endpoint_quarantine_total 891
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 18
telemt_me_single_endpoint_outage_reconnect_success_total 15
telemt_me_single_endpoint_quarantine_bypass_total 18
telemt_me_single_endpoint_shadow_rotate_total 936
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 48
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
telemt_desync_total 25518
telemt_desync_full_logged_total 8717
telemt_desync_suppressed_total 16801
telemt_desync_frames_bucket_total{bucket="1_2"} 6189
telemt_desync_frames_bucket_total{bucket="3_10"} 9808
telemt_desync_frames_bucket_total{bucket="gt_10"} 9521
telemt_pool_swap_total 135
telemt_pool_force_close_total 3990
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 458
telemt_me_draining_writers_reap_progress_total 42053
telemt_me_writer_removed_unexpected_total 1108
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3726
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 39439
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3692
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 298
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 38063
telemt_me_writer_teardown_success_total{mode="normal"} 43165
telemt_me_writer_teardown_noop_total 42065
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 81914
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 83582
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 84156
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 84780
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 85082
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 85178
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 85228
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 85228
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 85230
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 85230
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 85230
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 85230
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 85230
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 43.854808
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 85230
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 458
telemt_me_refill_failed_total 84
telemt_me_writer_restored_same_endpoint_total 1031
telemt_me_writer_restored_fallback_total 6
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 71
telemt_user_connections_total{user="hello"} 5469633
telemt_user_connections_current{user="hello"} 4484
telemt_user_octets_from_client{user="hello"} 144646022379 (134.71 GB)
telemt_user_octets_to_client{user="hello"} 2435136252799 (2.21 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 1828
telemt_user_unique_ips_recent_window{user="hello"} 509
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 126715.1 (35h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 23508503
telemt_connections_bad_total 1950327
telemt_connections_current 5542
telemt_connections_me_current 5542
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 686689
telemt_upstream_connect_attempt_total 240952
telemt_upstream_connect_success_total 221209
telemt_upstream_connect_fail_total 17756
telemt_upstream_connect_attempts_per_request{bucket="1"} 238965
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 155051
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 52261
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2724
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11173
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17756
telemt_me_keepalive_timeout_total 414
telemt_me_reconnect_attempts_total 66512
telemt_me_reconnect_success_total 2691
telemt_me_reader_eof_total 1671
telemt_me_idle_close_by_peer_total 1669
telemt_me_route_drop_no_conn_total 45190639
telemt_me_route_drop_channel_closed_total 144
telemt_me_route_drop_queue_full_total 15
telemt_me_route_drop_queue_full_profile_total{profile="high"} 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 18967983
telemt_me_writer_pick_total{mode="p2c",result="full"} 227
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_writer_pick_blocking_fallback_total 222
telemt_me_endpoint_quarantine_total 985
telemt_me_single_endpoint_outage_enter_total 164
telemt_me_single_endpoint_outage_exit_total 164
telemt_me_single_endpoint_outage_reconnect_attempt_total 335
telemt_me_single_endpoint_outage_reconnect_success_total 86
telemt_me_single_endpoint_quarantine_bypass_total 335
telemt_me_single_endpoint_shadow_rotate_total 996
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 71
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
telemt_desync_total 36762
telemt_desync_full_logged_total 10915
telemt_desync_suppressed_total 25847
telemt_desync_frames_bucket_total{bucket="1_2"} 8137
telemt_desync_frames_bucket_total{bucket="3_10"} 16250
telemt_desync_frames_bucket_total{bucket="gt_10"} 12375
telemt_pool_swap_total 131
telemt_pool_force_close_total 4154
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 958
telemt_me_draining_writers_reap_progress_total 39500
telemt_me_writer_removed_unexpected_total 2494
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5360
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 36365
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 29
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3565
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 589
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 35346
telemt_me_writer_teardown_success_total{mode="normal"} 41725
telemt_me_writer_teardown_noop_total 39532
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 73536
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 76406
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 77851
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 79715
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 80752
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 81119
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 81213
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 81222
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 81230
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 81241
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 81244
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 81252
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 81257
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 283.190299
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 81257
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 958
telemt_me_refill_failed_total 3863
telemt_me_writer_restored_same_endpoint_total 1820
telemt_me_writer_restored_fallback_total 22
telemt_me_no_writer_failfast_total 669
telemt_me_async_recovery_trigger_total 14757
telemt_me_writer_removed_unexpected_minus_restored_total 652
telemt_user_connections_total{user="hello"} 19133681
telemt_user_connections_current{user="hello"} 5542
telemt_user_octets_from_client{user="hello"} 275624983967 (256.70 GB)
telemt_user_octets_to_client{user="hello"} 1419749077075 (1.29 TB)
telemt_user_msgs_from_client{user="hello"} 503035
telemt_user_msgs_to_client{user="hello"} 1007896
telemt_user_unique_ips_current{user="hello"} 2065
telemt_user_unique_ips_recent_window{user="hello"} 1051
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 126682.7 (35h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6984864
telemt_connections_bad_total 638409
telemt_connections_current 4124
telemt_connections_me_current 4124
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 144501
telemt_upstream_connect_attempt_total 65757
telemt_upstream_connect_success_total 65010
telemt_upstream_connect_fail_total 641
telemt_upstream_connect_attempts_per_request{bucket="1"} 65651
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37157
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27487
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 365
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 641
telemt_me_reconnect_attempts_total 70106
telemt_me_reconnect_success_total 1941
telemt_me_reader_eof_total 1717
telemt_me_idle_close_by_peer_total 1716
telemt_me_route_drop_no_conn_total 2682797
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 40
telemt_me_route_drop_queue_full_profile_total{profile="high"} 40
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5473714
telemt_me_endpoint_quarantine_total 844
telemt_me_single_endpoint_outage_enter_total 24
telemt_me_single_endpoint_outage_exit_total 24
telemt_me_single_endpoint_outage_reconnect_attempt_total 25
telemt_me_single_endpoint_outage_reconnect_success_total 24
telemt_me_single_endpoint_quarantine_bypass_total 25
telemt_me_single_endpoint_shadow_rotate_total 962
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
telemt_desync_total 27530
telemt_desync_full_logged_total 9596
telemt_desync_suppressed_total 17934
telemt_desync_frames_bucket_total{bucket="1_2"} 5495
telemt_desync_frames_bucket_total{bucket="3_10"} 10586
telemt_desync_frames_bucket_total{bucket="gt_10"} 11449
telemt_pool_swap_total 132
telemt_pool_force_close_total 3796
telemt_pool_stale_pick_total 66
telemt_me_writer_close_signal_drop_total 448
telemt_me_draining_writers_reap_progress_total 44234
telemt_me_writer_removed_unexpected_total 1748
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4433
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 41586
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3377
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 419
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 40438
telemt_me_writer_teardown_success_total{mode="normal"} 46019
telemt_me_writer_teardown_noop_total 44235
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 88771
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 89709
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 90007
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 90220
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 90251
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 90254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 90254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 90254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 90254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 90254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 90254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 90254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 90254
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.080602
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 90254
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 448
telemt_me_refill_failed_total 4221
telemt_me_writer_restored_same_endpoint_total 1620
telemt_me_writer_restored_fallback_total 38
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7313
telemt_me_writer_removed_unexpected_minus_restored_total 90
telemt_user_connections_total{user="hello"} 5464734
telemt_user_connections_current{user="hello"} 4124
telemt_user_octets_from_client{user="hello"} 138673051376 (129.15 GB)
telemt_user_octets_to_client{user="hello"} 2284476550038 (2.08 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 1720
telemt_user_unique_ips_recent_window{user="hello"} 555
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 63518.6 (17h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5311023
telemt_connections_bad_total 212668
telemt_connections_current 3271
telemt_connections_me_current 3271
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 2113744
telemt_upstream_connect_attempt_total 34665
telemt_upstream_connect_success_total 34423
telemt_upstream_connect_fail_total 235
telemt_upstream_connect_attempts_per_request{bucket="1"} 34658
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20590
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13745
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 88
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 235
telemt_me_reconnect_attempts_total 46313
telemt_me_reconnect_success_total 1086
telemt_me_reader_eof_total 778
telemt_me_idle_close_by_peer_total 778
telemt_me_route_drop_no_conn_total 1295624
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2646417
telemt_me_endpoint_quarantine_total 441
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 51
telemt_me_single_endpoint_outage_reconnect_success_total 12
telemt_me_single_endpoint_quarantine_bypass_total 51
telemt_me_single_endpoint_shadow_rotate_total 489
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
telemt_me_writers_active_current 43
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 14195
telemt_desync_full_logged_total 4870
telemt_desync_suppressed_total 9325
telemt_desync_frames_bucket_total{bucket="1_2"} 2792
telemt_desync_frames_bucket_total{bucket="3_10"} 5445
telemt_desync_frames_bucket_total{bucket="gt_10"} 5958
telemt_pool_swap_total 69
telemt_pool_force_close_total 2031
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 187
telemt_me_draining_writers_reap_progress_total 22995
telemt_me_writer_removed_unexpected_total 848
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1939
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21926
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1800
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 231
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20964
telemt_me_writer_teardown_success_total{mode="normal"} 23865
telemt_me_writer_teardown_noop_total 22997
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 46212
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 46561
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 46736
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 46862
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 46862
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 46862
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 46862
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 46862
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 46862
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 46862
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 46862
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 46862
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 46862
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.281093
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 46862
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 187
telemt_me_refill_failed_total 2627
telemt_me_writer_restored_same_endpoint_total 965
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4264
telemt_user_connections_total{user="hello"} 2647926
telemt_user_connections_current{user="hello"} 3271
telemt_user_octets_from_client{user="hello"} 67063585812 (62.46 GB)
telemt_user_octets_to_client{user="hello"} 1174058752078 (1.07 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 1393
telemt_user_unique_ips_recent_window{user="hello"} 540
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 44489.4 (12h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 358940
telemt_connections_bad_total 2479
telemt_connections_current 884
telemt_connections_me_current 884
telemt_handshake_timeouts_total 7817
telemt_upstream_connect_attempt_total 21201
telemt_upstream_connect_success_total 21147
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 21197
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8884
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12121
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 142
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_reconnect_attempts_total 925
telemt_me_reconnect_success_total 311
telemt_me_reader_eof_total 310
telemt_me_idle_close_by_peer_total 310
telemt_me_route_drop_no_conn_total 111012
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 325721
telemt_me_endpoint_quarantine_total 424
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 386
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
telemt_me_writers_active_current 44
telemt_desync_total 1516
telemt_desync_full_logged_total 431
telemt_desync_suppressed_total 1085
telemt_desync_frames_bucket_total{bucket="1_2"} 482
telemt_desync_frames_bucket_total{bucket="3_10"} 584
telemt_desync_frames_bucket_total{bucket="gt_10"} 450
telemt_pool_swap_total 49
telemt_pool_force_close_total 1112
telemt_me_writer_close_signal_drop_total 41
telemt_me_draining_writers_reap_progress_total 19154
telemt_me_writer_removed_unexpected_total 296
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1264
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18200
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1110
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18042
telemt_me_writer_teardown_success_total{mode="normal"} 19464
telemt_me_writer_teardown_noop_total 19154
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 38281
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 38547
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 38608
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 38618
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 38618
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 38618
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 38618
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 38618
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 38618
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 38618
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 38618
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 38618
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 38618
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.797162
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 38618
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 41
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 265
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 325162
telemt_user_connections_current{user="hello"} 884
telemt_user_octets_from_client{user="hello"} 5537427148 (5.16 GB)
telemt_user_octets_to_client{user="hello"} 177622217164 (165.42 GB)
telemt_user_unique_ips_current{user="hello"} 328
telemt_user_unique_ips_recent_window{user="hello"} 147
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 126686.9 (35h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8556744
telemt_connections_bad_total 934105
telemt_connections_current 4651
telemt_connections_me_current 4651
telemt_handshake_timeouts_total 240822
telemt_upstream_connect_attempt_total 49528
telemt_upstream_connect_success_total 49347
telemt_upstream_connect_fail_total 142
telemt_upstream_connect_attempts_per_request{bucket="1"} 49489
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24438
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24868
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 142
telemt_me_reconnect_attempts_total 1837
telemt_me_reconnect_success_total 999
telemt_me_reader_eof_total 977
telemt_me_idle_close_by_peer_total 977
telemt_me_route_drop_no_conn_total 2396379
telemt_me_route_drop_channel_closed_total 57
telemt_me_route_drop_queue_full_total 23
telemt_me_route_drop_queue_full_profile_total{profile="high"} 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6355821
telemt_me_endpoint_quarantine_total 895
telemt_me_single_endpoint_outage_enter_total 10
telemt_me_single_endpoint_outage_exit_total 10
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 965
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
telemt_me_writers_active_current 44
telemt_desync_total 25419
telemt_desync_full_logged_total 8358
telemt_desync_suppressed_total 17061
telemt_desync_frames_bucket_total{bucket="1_2"} 6302
telemt_desync_frames_bucket_total{bucket="3_10"} 9256
telemt_desync_frames_bucket_total{bucket="gt_10"} 9861
telemt_pool_swap_total 140
telemt_pool_force_close_total 3749
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 449
telemt_me_draining_writers_reap_progress_total 44691
telemt_me_writer_removed_unexpected_total 938
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3534
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 42124
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3653
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 96
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 40942
telemt_me_writer_teardown_success_total{mode="normal"} 45658
telemt_me_writer_teardown_noop_total 44693
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 88818
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 89854
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 90050
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 90260
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 90351
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 90351
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 90351
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 90351
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 90351
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 90351
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 90351
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 90351
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 90351
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 11.545710
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 90351
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 449
telemt_me_refill_failed_total 43
telemt_me_writer_restored_same_endpoint_total 883
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 24
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 6329336
telemt_user_connections_current{user="hello"} 4651
telemt_user_octets_from_client{user="hello"} 124808601900 (116.24 GB)
telemt_user_octets_to_client{user="hello"} 2968592006300 (2.70 TB)
telemt_user_unique_ips_current{user="hello"} 1752
telemt_user_unique_ips_recent_window{user="hello"} 635
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 126683.7 (35h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7478276
telemt_connections_bad_total 815001
telemt_connections_current 3927
telemt_connections_me_current 3927
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 200295
telemt_upstream_connect_attempt_total 65567
telemt_upstream_connect_success_total 65063
telemt_upstream_connect_fail_total 441
telemt_upstream_connect_attempts_per_request{bucket="1"} 65504
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37330
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26591
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 624
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 441
telemt_me_reconnect_attempts_total 6124
telemt_me_reconnect_success_total 1410
telemt_me_reader_eof_total 1268
telemt_me_idle_close_by_peer_total 1268
telemt_me_seq_mismatch_total 61
telemt_me_route_drop_no_conn_total 2501304
telemt_me_route_drop_channel_closed_total 205
telemt_me_route_drop_queue_full_total 14
telemt_me_route_drop_queue_full_profile_total{profile="high"} 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5686089
telemt_me_endpoint_quarantine_total 992
telemt_me_single_endpoint_outage_enter_total 30
telemt_me_single_endpoint_outage_exit_total 30
telemt_me_single_endpoint_outage_reconnect_attempt_total 30
telemt_me_single_endpoint_outage_reconnect_success_total 28
telemt_me_single_endpoint_quarantine_bypass_total 30
telemt_me_single_endpoint_shadow_rotate_total 964
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
telemt_me_writers_active_current 49
telemt_desync_total 24321
telemt_desync_full_logged_total 8092
telemt_desync_suppressed_total 16229
telemt_desync_frames_bucket_total{bucket="1_2"} 6013
telemt_desync_frames_bucket_total{bucket="3_10"} 8921
telemt_desync_frames_bucket_total{bucket="gt_10"} 9387
telemt_pool_swap_total 137
telemt_pool_force_close_total 3693
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 448
telemt_me_draining_writers_reap_progress_total 43356
telemt_me_writer_removed_unexpected_total 1283
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4134
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 40566
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3435
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 258
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 39663
telemt_me_writer_teardown_success_total{mode="normal"} 44700
telemt_me_writer_teardown_noop_total 43360
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 86168
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 87356
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 87797
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 88022
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 88060
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 88060
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 88060
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 88060
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 88060
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 88060
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 88060
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 88060
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 88060
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 12.604364
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 88060
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 448
telemt_me_refill_failed_total 272
telemt_me_writer_restored_same_endpoint_total 1105
telemt_me_writer_restored_fallback_total 81
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 102
telemt_me_writer_removed_unexpected_minus_restored_total 97
telemt_user_connections_total{user="hello"} 5687600
telemt_user_connections_current{user="hello"} 3927
telemt_user_octets_from_client{user="hello"} 104896842925 (97.69 GB)
telemt_user_octets_to_client{user="hello"} 2472289211584 (2.25 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1562
telemt_user_unique_ips_recent_window{user="hello"} 580
```