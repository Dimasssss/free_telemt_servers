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

# Server Metrics 2026-03-22 02:00:02 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 17620.1 (4h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 253557
telemt_connections_bad_total 18128
telemt_connections_current 753
telemt_connections_me_current 753
telemt_handshake_timeouts_total 14658
telemt_upstream_connect_attempt_total 7370
telemt_upstream_connect_success_total 7369
telemt_upstream_connect_attempts_per_request{bucket="1"} 7369
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2689
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4666
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 247
telemt_me_reconnect_success_total 121
telemt_me_reader_eof_total 119
telemt_me_idle_close_by_peer_total 119
telemt_me_route_drop_no_conn_total 46769
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 206962
telemt_me_endpoint_quarantine_total 144
telemt_me_single_endpoint_shadow_rotate_total 150
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 2
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
telemt_desync_total 1837
telemt_desync_full_logged_total 503
telemt_desync_suppressed_total 1334
telemt_desync_frames_bucket_total{bucket="1_2"} 586
telemt_desync_frames_bucket_total{bucket="3_10"} 671
telemt_desync_frames_bucket_total{bucket="gt_10"} 580
telemt_pool_swap_total 19
telemt_pool_force_close_total 494
telemt_me_writer_close_signal_drop_total 33
telemt_me_draining_writers_reap_progress_total 6609
telemt_me_writer_removed_unexpected_total 119
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 467
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 6251
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 489
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 6115
telemt_me_writer_teardown_success_total{mode="normal"} 6718
telemt_me_writer_teardown_noop_total 6610
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 12933
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 13172
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 13250
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 13302
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 13326
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 13328
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 13328
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 13328
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 13328
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 13328
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 13328
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 13328
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 13328
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.197243
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 13328
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 33
telemt_me_refill_failed_total 7
telemt_me_writer_restored_same_endpoint_total 110
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 206587
telemt_user_connections_current{user="hello"} 753
telemt_user_octets_from_client{user="hello"} 2208576384 (2.06 GB)
telemt_user_octets_to_client{user="hello"} 71334809272 (66.44 GB)
telemt_user_unique_ips_current{user="hello"} 348
telemt_user_unique_ips_recent_window{user="hello"} 79
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 30986.1 (8h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 755595
telemt_connections_bad_total 43508
telemt_connections_current 359
telemt_connections_me_current 359
telemt_handshake_timeouts_total 28051
telemt_upstream_connect_attempt_total 14265
telemt_upstream_connect_success_total 14034
telemt_upstream_connect_fail_total 210
telemt_upstream_connect_attempts_per_request{bucket="1"} 14244
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6192
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7800
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 210
telemt_me_reconnect_attempts_total 1223
telemt_me_reconnect_success_total 455
telemt_me_reader_eof_total 398
telemt_me_idle_close_by_peer_total 398
telemt_me_route_drop_no_conn_total 336995
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 603596
telemt_me_endpoint_quarantine_total 298
telemt_me_single_endpoint_outage_enter_total 17
telemt_me_single_endpoint_outage_exit_total 17
telemt_me_single_endpoint_outage_reconnect_attempt_total 17
telemt_me_single_endpoint_outage_reconnect_success_total 17
telemt_me_single_endpoint_quarantine_bypass_total 17
telemt_me_single_endpoint_shadow_rotate_total 253
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 18
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
telemt_me_writers_active_current 47
telemt_desync_total 2640
telemt_desync_full_logged_total 1508
telemt_desync_suppressed_total 1132
telemt_desync_frames_bucket_total{bucket="1_2"} 561
telemt_desync_frames_bucket_total{bucket="3_10"} 1001
telemt_desync_frames_bucket_total{bucket="gt_10"} 1078
telemt_pool_swap_total 33
telemt_pool_force_close_total 909
telemt_me_writer_close_signal_drop_total 64
telemt_me_draining_writers_reap_progress_total 12621
telemt_me_writer_removed_unexpected_total 379
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1079
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 11927
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 887
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 22
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 11712
telemt_me_writer_teardown_success_total{mode="normal"} 13006
telemt_me_writer_teardown_noop_total 12621
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 25140
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 25432
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 25521
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 25613
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 25625
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 25627
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 25627
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 25627
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 25627
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 25627
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 25627
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 25627
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 25627
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.534980
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 25627
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 64
telemt_me_refill_failed_total 40
telemt_me_writer_restored_same_endpoint_total 334
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 602705
telemt_user_connections_current{user="hello"} 359
telemt_user_octets_from_client{user="hello"} 9965278124 (9.28 GB)
telemt_user_octets_to_client{user="hello"} 215833968320 (201.01 GB)
telemt_user_unique_ips_current{user="hello"} 276
telemt_user_unique_ips_recent_window{user="hello"} 113
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 105846.1 (29h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7664316
telemt_connections_bad_total 621634
telemt_connections_current 1573
telemt_connections_me_current 1573
telemt_handshake_timeouts_total 251609
telemt_upstream_connect_attempt_total 39045
telemt_upstream_connect_success_total 38972
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 38979
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17668
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21131
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 167
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1555
telemt_me_reconnect_success_total 793
telemt_me_reader_eof_total 804
telemt_me_idle_close_by_peer_total 804
telemt_me_route_drop_no_conn_total 4526131
telemt_me_route_drop_channel_closed_total 66
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6213966
telemt_me_endpoint_quarantine_total 681
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 791
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 25
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
telemt_desync_total 26263
telemt_desync_full_logged_total 8681
telemt_desync_suppressed_total 17582
telemt_desync_frames_bucket_total{bucket="1_2"} 5653
telemt_desync_frames_bucket_total{bucket="3_10"} 10247
telemt_desync_frames_bucket_total{bucket="gt_10"} 10363
telemt_pool_swap_total 114
telemt_pool_force_close_total 3810
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 598
telemt_me_draining_writers_reap_progress_total 35636
telemt_me_writer_removed_unexpected_total 773
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2979
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 32974
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3571
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 239
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 31826
telemt_me_writer_teardown_success_total{mode="normal"} 35953
telemt_me_writer_teardown_noop_total 35680
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 65449
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 67296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 68298
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 69799
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 70793
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 71332
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 71622
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 71633
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 71633
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 71633
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 71633
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 71633
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 71633
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 157.442362
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 71633
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 598
telemt_me_refill_failed_total 40
telemt_me_writer_restored_same_endpoint_total 706
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 62
telemt_user_connections_total{user="hello"} 6206167
telemt_user_connections_current{user="hello"} 1573
telemt_user_octets_from_client{user="hello"} 105791793668 (98.53 GB)
telemt_user_octets_to_client{user="hello"} 2059484335372 (1.87 TB)
telemt_user_unique_ips_current{user="hello"} 802
telemt_user_unique_ips_recent_window{user="hello"} 169
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 105847.3 (29h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6320149
telemt_connections_bad_total 584996
telemt_connections_current 1459
telemt_connections_me_current 1459
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 209417
telemt_upstream_connect_attempt_total 43072
telemt_upstream_connect_success_total 42686
telemt_upstream_connect_fail_total 189
telemt_upstream_connect_attempts_per_request{bucket="1"} 42875
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21225
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20873
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 555
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 189
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 1916
telemt_me_reconnect_success_total 863
telemt_me_reader_eof_total 833
telemt_me_idle_close_by_peer_total 833
telemt_me_route_drop_no_conn_total 2248020
telemt_me_route_drop_channel_closed_total 257
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4732034
telemt_me_endpoint_quarantine_total 658
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 813
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 29
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
telemt_desync_total 22456
telemt_desync_full_logged_total 7632
telemt_desync_suppressed_total 14824
telemt_desync_frames_bucket_total{bucket="1_2"} 5410
telemt_desync_frames_bucket_total{bucket="3_10"} 8718
telemt_desync_frames_bucket_total{bucket="gt_10"} 8328
telemt_pool_swap_total 115
telemt_pool_force_close_total 3444
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 358
telemt_me_draining_writers_reap_progress_total 34155
telemt_me_writer_removed_unexpected_total 818
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2888
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 32022
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3231
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 213
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 30711
telemt_me_writer_teardown_success_total{mode="normal"} 34910
telemt_me_writer_teardown_noop_total 34161
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 65778
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 67309
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 67878
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 68455
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 68866
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 69051
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 69071
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 69071
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 69071
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 69071
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 69071
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 69071
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 69071
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 48.256400
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 69071
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 358
telemt_me_refill_failed_total 56
telemt_me_writer_restored_same_endpoint_total 754
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 56
telemt_user_connections_total{user="hello"} 4654278
telemt_user_connections_current{user="hello"} 1459
telemt_user_octets_from_client{user="hello"} 139778969945 (130.18 GB)
telemt_user_octets_to_client{user="hello"} 2190656181431 (1.99 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 758
telemt_user_unique_ips_recent_window{user="hello"} 142
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 105811.6 (29h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6204928
telemt_connections_bad_total 545845
telemt_connections_current 1465
telemt_connections_me_current 1465
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 200116
telemt_upstream_connect_attempt_total 49351
telemt_upstream_connect_success_total 48997
telemt_upstream_connect_fail_total 136
telemt_upstream_connect_attempts_per_request{bucket="1"} 49133
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25250
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22248
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 437
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1062
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 136
telemt_me_keepalive_timeout_total 58
telemt_me_reconnect_attempts_total 1957
telemt_me_reconnect_success_total 882
telemt_me_reader_eof_total 826
telemt_me_idle_close_by_peer_total 826
telemt_me_route_drop_no_conn_total 2140674
telemt_me_route_drop_channel_closed_total 117
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4624933
telemt_me_endpoint_quarantine_total 736
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 793
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 38
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
telemt_desync_total 22290
telemt_desync_full_logged_total 7479
telemt_desync_suppressed_total 14811
telemt_desync_frames_bucket_total{bucket="1_2"} 5447
telemt_desync_frames_bucket_total{bucket="3_10"} 8541
telemt_desync_frames_bucket_total{bucket="gt_10"} 8302
telemt_pool_swap_total 114
telemt_pool_force_close_total 3314
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 379
telemt_me_draining_writers_reap_progress_total 35497
telemt_me_writer_removed_unexpected_total 799
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2936
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 33373
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3099
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 215
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 32183
telemt_me_writer_teardown_success_total{mode="normal"} 36309
telemt_me_writer_teardown_noop_total 35508
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 69298
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 70670
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 71109
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 71567
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 71774
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 71799
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 71817
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 71817
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 71817
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 71817
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 71817
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 71817
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 71817
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 25.757256
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 71817
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 379
telemt_me_refill_failed_total 59
telemt_me_writer_restored_same_endpoint_total 766
telemt_me_writer_restored_fallback_total 5
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 28
telemt_user_connections_total{user="hello"} 4620611
telemt_user_connections_current{user="hello"} 1465
telemt_user_octets_from_client{user="hello"} 133081898391 (123.94 GB)
telemt_user_octets_to_client{user="hello"} 2110758758131 (1.92 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 701
telemt_user_unique_ips_recent_window{user="hello"} 160
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 105850.7 (29h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20297844
telemt_connections_bad_total 1583555
telemt_connections_current 2012
telemt_connections_me_current 2012
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 597912
telemt_upstream_connect_attempt_total 194406
telemt_upstream_connect_success_total 176468
telemt_upstream_connect_fail_total 16222
telemt_upstream_connect_attempts_per_request{bucket="1"} 192690
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 124459
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 41877
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1221
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8911
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16222
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 64823
telemt_me_reconnect_success_total 2289
telemt_me_reader_eof_total 1428
telemt_me_idle_close_by_peer_total 1427
telemt_me_route_drop_no_conn_total 39492634
telemt_me_route_drop_channel_closed_total 124
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16437227
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 828
telemt_me_single_endpoint_outage_enter_total 133
telemt_me_single_endpoint_outage_exit_total 133
telemt_me_single_endpoint_outage_reconnect_attempt_total 283
telemt_me_single_endpoint_outage_reconnect_success_total 68
telemt_me_single_endpoint_quarantine_bypass_total 283
telemt_me_single_endpoint_shadow_rotate_total 830
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 62
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
telemt_desync_total 31849
telemt_desync_full_logged_total 9526
telemt_desync_suppressed_total 22323
telemt_desync_frames_bucket_total{bucket="1_2"} 6901
telemt_desync_frames_bucket_total{bucket="3_10"} 14133
telemt_desync_frames_bucket_total{bucket="gt_10"} 10815
telemt_pool_swap_total 109
telemt_pool_force_close_total 3574
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 790
telemt_me_draining_writers_reap_progress_total 33034
telemt_me_writer_removed_unexpected_total 2129
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4482
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 30419
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3051
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 523
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 29460
telemt_me_writer_teardown_success_total{mode="normal"} 34901
telemt_me_writer_teardown_noop_total 33060
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 61204
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 63656
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 64929
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 66574
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 67517
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 67859
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 67942
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 67944
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 67947
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 67952
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 67952
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 67956
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 67961
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 214.626497
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 67961
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 790
telemt_me_refill_failed_total 3801
telemt_me_writer_restored_same_endpoint_total 1570
telemt_me_writer_restored_fallback_total 21
telemt_me_no_writer_failfast_total 666
telemt_me_async_recovery_trigger_total 14678
telemt_me_writer_removed_unexpected_minus_restored_total 538
telemt_user_connections_total{user="hello"} 16566775
telemt_user_connections_current{user="hello"} 2012
telemt_user_octets_from_client{user="hello"} 210551163962 (196.09 GB)
telemt_user_octets_to_client{user="hello"} 1177523520039 (1.07 TB)
telemt_user_msgs_from_client{user="hello"} 373576
telemt_user_msgs_to_client{user="hello"} 663916
telemt_user_unique_ips_current{user="hello"} 990
telemt_user_unique_ips_recent_window{user="hello"} 212
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 105818.2 (29h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5966760
telemt_connections_bad_total 558797
telemt_connections_current 1565
telemt_connections_me_current 1565
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 124594
telemt_upstream_connect_attempt_total 57765
telemt_upstream_connect_success_total 57090
telemt_upstream_connect_fail_total 578
telemt_upstream_connect_attempts_per_request{bucket="1"} 57668
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33500
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23242
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 347
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 578
telemt_me_reconnect_attempts_total 69628
telemt_me_reconnect_success_total 1768
telemt_me_reader_eof_total 1546
telemt_me_idle_close_by_peer_total 1545
telemt_me_route_drop_no_conn_total 2380719
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4656782
telemt_me_endpoint_quarantine_total 714
telemt_me_single_endpoint_outage_enter_total 23
telemt_me_single_endpoint_outage_exit_total 23
telemt_me_single_endpoint_outage_reconnect_attempt_total 24
telemt_me_single_endpoint_outage_reconnect_success_total 23
telemt_me_single_endpoint_quarantine_bypass_total 24
telemt_me_single_endpoint_shadow_rotate_total 800
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
telemt_desync_total 23265
telemt_desync_full_logged_total 8182
telemt_desync_suppressed_total 15083
telemt_desync_frames_bucket_total{bucket="1_2"} 4423
telemt_desync_frames_bucket_total{bucket="3_10"} 9003
telemt_desync_frames_bucket_total{bucket="gt_10"} 9839
telemt_pool_swap_total 109
telemt_pool_force_close_total 3157
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 390
telemt_me_draining_writers_reap_progress_total 37089
telemt_me_writer_removed_unexpected_total 1585
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3844
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 34860
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2756
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 401
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 33932
telemt_me_writer_teardown_success_total{mode="normal"} 38704
telemt_me_writer_teardown_noop_total 37090
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 74541
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 75363
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 75642
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 75762
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 75791
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 75794
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 75794
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 75794
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 75794
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 75794
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 75794
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 75794
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 75794
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.104402
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 75794
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 390
telemt_me_refill_failed_total 4206
telemt_me_writer_restored_same_endpoint_total 1480
telemt_me_writer_restored_fallback_total 33
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7305
telemt_me_writer_removed_unexpected_minus_restored_total 72
telemt_user_connections_total{user="hello"} 4649699
telemt_user_connections_current{user="hello"} 1565
telemt_user_octets_from_client{user="hello"} 123720802372 (115.22 GB)
telemt_user_octets_to_client{user="hello"} 1899213590050 (1.73 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 787
telemt_user_unique_ips_recent_window{user="hello"} 143
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 42654.1 (11h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3855830
telemt_connections_bad_total 139766
telemt_connections_current 1051
telemt_connections_me_current 1051
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 1578741
telemt_upstream_connect_attempt_total 26223
telemt_upstream_connect_success_total 26052
telemt_upstream_connect_fail_total 164
telemt_upstream_connect_attempts_per_request{bucket="1"} 26216
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16667
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9312
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 73
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 164
telemt_me_reconnect_attempts_total 45798
telemt_me_reconnect_success_total 946
telemt_me_reader_eof_total 625
telemt_me_idle_close_by_peer_total 625
telemt_me_route_drop_no_conn_total 1014705
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1887061
telemt_me_endpoint_quarantine_total 320
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 50
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 50
telemt_me_single_endpoint_shadow_rotate_total 327
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 9
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
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 10315
telemt_desync_full_logged_total 3556
telemt_desync_suppressed_total 6759
telemt_desync_frames_bucket_total{bucket="1_2"} 1837
telemt_desync_frames_bucket_total{bucket="3_10"} 3961
telemt_desync_frames_bucket_total{bucket="gt_10"} 4517
telemt_pool_swap_total 46
telemt_pool_force_close_total 1429
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 132
telemt_me_draining_writers_reap_progress_total 15389
telemt_me_writer_removed_unexpected_total 702
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1469
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14645
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1223
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 206
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13960
telemt_me_writer_teardown_success_total{mode="normal"} 16114
telemt_me_writer_teardown_noop_total 15391
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 31005
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 31282
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 31399
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 31505
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 31505
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 31505
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 31505
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 31505
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 31505
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 31505
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 31505
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 31505
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 31505
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.345457
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 31505
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 132
telemt_me_refill_failed_total 2606
telemt_me_writer_restored_same_endpoint_total 847
telemt_me_writer_restored_fallback_total 12
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4264
telemt_user_connections_total{user="hello"} 1890725
telemt_user_connections_current{user="hello"} 1051
telemt_user_octets_from_client{user="hello"} 53612638160 (49.93 GB)
telemt_user_octets_to_client{user="hello"} 806664392802 (751.26 GB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 573
telemt_user_unique_ips_recent_window{user="hello"} 130
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 23624.9 (6h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 186761
telemt_connections_bad_total 1624
telemt_connections_current 293
telemt_connections_me_current 293
telemt_handshake_timeouts_total 5183
telemt_upstream_connect_attempt_total 11309
telemt_upstream_connect_success_total 11281
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 11307
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4781
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6426
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 74
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_reconnect_attempts_total 232
telemt_me_reconnect_success_total 146
telemt_me_reader_eof_total 149
telemt_me_idle_close_by_peer_total 149
telemt_me_route_drop_no_conn_total 50935
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 164446
telemt_me_endpoint_quarantine_total 239
telemt_me_single_endpoint_shadow_rotate_total 209
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 3
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
telemt_desync_total 1008
telemt_desync_full_logged_total 254
telemt_desync_suppressed_total 754
telemt_desync_frames_bucket_total{bucket="1_2"} 389
telemt_desync_frames_bucket_total{bucket="3_10"} 369
telemt_desync_frames_bucket_total{bucket="gt_10"} 250
telemt_pool_swap_total 26
telemt_pool_force_close_total 582
telemt_me_writer_close_signal_drop_total 22
telemt_me_draining_writers_reap_progress_total 10198
telemt_me_writer_removed_unexpected_total 144
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 672
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 9675
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 580
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 9616
telemt_me_writer_teardown_success_total{mode="normal"} 10347
telemt_me_writer_teardown_noop_total 10198
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 20350
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 20517
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 20535
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 20545
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 20545
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 20545
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 20545
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 20545
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 20545
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 20545
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 20545
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 20545
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 20545
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.953898
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 20545
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 22
telemt_me_refill_failed_total 5
telemt_me_writer_restored_same_endpoint_total 134
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 164137
telemt_user_connections_current{user="hello"} 293
telemt_user_octets_from_client{user="hello"} 3005799040 (2.80 GB)
telemt_user_octets_to_client{user="hello"} 97358313736 (90.67 GB)
telemt_user_unique_ips_current{user="hello"} 129
telemt_user_unique_ips_recent_window{user="hello"} 53
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 105822.6 (29h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7250460
telemt_connections_bad_total 737885
telemt_connections_current 1758
telemt_connections_me_current 1758
telemt_handshake_timeouts_total 206372
telemt_upstream_connect_attempt_total 41297
telemt_upstream_connect_success_total 41143
telemt_upstream_connect_fail_total 117
telemt_upstream_connect_attempts_per_request{bucket="1"} 41260
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20388
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20714
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 117
telemt_me_reconnect_attempts_total 1551
telemt_me_reconnect_success_total 834
telemt_me_reader_eof_total 816
telemt_me_idle_close_by_peer_total 816
telemt_me_route_drop_no_conn_total 2118153
telemt_me_route_drop_channel_closed_total 52
telemt_me_route_drop_queue_full_total 23
telemt_me_route_drop_queue_full_profile_total{profile="high"} 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5435271
telemt_me_endpoint_quarantine_total 733
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 814
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 30
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
telemt_me_writers_active_current 47
telemt_desync_total 21360
telemt_desync_full_logged_total 7003
telemt_desync_suppressed_total 14357
telemt_desync_frames_bucket_total{bucket="1_2"} 5366
telemt_desync_frames_bucket_total{bucket="3_10"} 7731
telemt_desync_frames_bucket_total{bucket="gt_10"} 8263
telemt_pool_swap_total 117
telemt_pool_force_close_total 3149
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 383
telemt_me_draining_writers_reap_progress_total 37233
telemt_me_writer_removed_unexpected_total 787
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2941
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 35098
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3061
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 34084
telemt_me_writer_teardown_success_total{mode="normal"} 38039
telemt_me_writer_teardown_noop_total 37235
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 73922
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 74808
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 74986
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 75186
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 75274
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 75274
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 75274
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 75274
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 75274
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 75274
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 75274
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 75274
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 75274
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.620721
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 75274
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 383
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 744
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 5410301
telemt_user_connections_current{user="hello"} 1758
telemt_user_octets_from_client{user="hello"} 108750374044 (101.28 GB)
telemt_user_octets_to_client{user="hello"} 2524122383872 (2.30 TB)
telemt_user_unique_ips_current{user="hello"} 777
telemt_user_unique_ips_recent_window{user="hello"} 147
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 105819.3 (29h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6250393
telemt_connections_bad_total 617050
telemt_connections_current 1384
telemt_connections_me_current 1384
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 171705
telemt_upstream_connect_attempt_total 57068
telemt_upstream_connect_success_total 56642
telemt_upstream_connect_fail_total 367
telemt_upstream_connect_attempts_per_request{bucket="1"} 57009
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33117
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22392
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 615
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 367
telemt_me_reconnect_attempts_total 5542
telemt_me_reconnect_success_total 1145
telemt_me_reader_eof_total 1027
telemt_me_idle_close_by_peer_total 1027
telemt_me_seq_mismatch_total 47
telemt_me_route_drop_no_conn_total 2171542
telemt_me_route_drop_channel_closed_total 189
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4802763
telemt_me_endpoint_quarantine_total 843
telemt_me_single_endpoint_outage_enter_total 28
telemt_me_single_endpoint_outage_exit_total 28
telemt_me_single_endpoint_outage_reconnect_attempt_total 28
telemt_me_single_endpoint_outage_reconnect_success_total 26
telemt_me_single_endpoint_quarantine_bypass_total 28
telemt_me_single_endpoint_shadow_rotate_total 811
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
telemt_desync_total 19995
telemt_desync_full_logged_total 6647
telemt_desync_suppressed_total 13348
telemt_desync_frames_bucket_total{bucket="1_2"} 5106
telemt_desync_frames_bucket_total{bucket="3_10"} 7282
telemt_desync_frames_bucket_total{bucket="gt_10"} 7607
telemt_pool_swap_total 115
telemt_pool_force_close_total 3105
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 376
telemt_me_draining_writers_reap_progress_total 35790
telemt_me_writer_removed_unexpected_total 1041
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3455
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 33424
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2882
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 223
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 32685
telemt_me_writer_teardown_success_total{mode="normal"} 36879
telemt_me_writer_teardown_noop_total 35794
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 71045
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 72095
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 72440
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 72635
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 72673
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 72673
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 72673
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 72673
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 72673
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 72673
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 72673
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 72673
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 72673
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.998868
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 72673
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 376
telemt_me_refill_failed_total 254
telemt_me_writer_restored_same_endpoint_total 891
telemt_me_writer_restored_fallback_total 60
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 76
telemt_me_writer_removed_unexpected_minus_restored_total 90
telemt_user_connections_total{user="hello"} 4805866
telemt_user_connections_current{user="hello"} 1384
telemt_user_octets_from_client{user="hello"} 90284001133 (84.08 GB)
telemt_user_octets_to_client{user="hello"} 2054286479328 (1.87 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 692
telemt_user_unique_ips_recent_window{user="hello"} 149
```