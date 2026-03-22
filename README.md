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

# Server Metrics 2026-03-22 13:56:11 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 60588.6 (16h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1909174
telemt_connections_bad_total 83072
telemt_connections_current 1626
telemt_connections_me_current 1626
telemt_handshake_timeouts_total 80033
telemt_upstream_connect_attempt_total 22702
telemt_upstream_connect_success_total 22701
telemt_upstream_connect_attempts_per_request{bucket="1"} 22701
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7867
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14769
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 52
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 915
telemt_me_reconnect_success_total 369
telemt_me_reader_eof_total 373
telemt_me_idle_close_by_peer_total 373
telemt_me_route_drop_no_conn_total 1325791
telemt_me_route_drop_channel_closed_total 608
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1624568
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_endpoint_quarantine_total 418
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 480
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
telemt_me_writers_active_current 44
telemt_desync_total 8865
telemt_desync_full_logged_total 2721
telemt_desync_suppressed_total 6144
telemt_desync_frames_bucket_total{bucket="1_2"} 2464
telemt_desync_frames_bucket_total{bucket="3_10"} 3335
telemt_desync_frames_bucket_total{bucket="gt_10"} 3066
telemt_pool_swap_total 67
telemt_pool_force_close_total 2004
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 327
telemt_me_draining_writers_reap_progress_total 20702
telemt_me_writer_removed_unexpected_total 364
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1478
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19447
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1968
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 36
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18698
telemt_me_writer_teardown_success_total{mode="normal"} 20925
telemt_me_writer_teardown_noop_total 20706
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 35211
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 36494
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 37627
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 39526
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 40847
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 41467
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 41628
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 41631
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 41631
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 41631
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 41631
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 41631
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 41631
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 157.682008
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 41631
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 327
telemt_me_refill_failed_total 29
telemt_me_writer_restored_same_endpoint_total 327
telemt_me_writer_removed_unexpected_minus_restored_total 37
telemt_user_connections_total{user="hello"} 1621627
telemt_user_connections_current{user="hello"} 1626
telemt_user_octets_from_client{user="hello"} 25525418120 (23.77 GB)
telemt_user_octets_to_client{user="hello"} 474829683904 (442.22 GB)
telemt_user_unique_ips_current{user="hello"} 636
telemt_user_unique_ips_recent_window{user="hello"} 282
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 73954.8 (20h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3086909
telemt_connections_bad_total 287657
telemt_connections_current 2391
telemt_connections_me_current 2391
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 73345
telemt_upstream_connect_attempt_total 47420
telemt_upstream_connect_success_total 46850
telemt_upstream_connect_fail_total 505
telemt_upstream_connect_attempts_per_request{bucket="1"} 47355
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28065
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18648
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 137
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 505
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 3715
telemt_me_reconnect_success_total 1693
telemt_me_reader_eof_total 1567
telemt_me_idle_close_by_peer_total 1567
telemt_me_route_drop_no_conn_total 2893540
telemt_me_route_drop_channel_closed_total 29
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2430179
telemt_me_endpoint_quarantine_total 612
telemt_me_single_endpoint_outage_enter_total 35
telemt_me_single_endpoint_outage_exit_total 35
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 35
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 575
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
telemt_me_writers_active_current 101
telemt_me_writers_warm_current 25
telemt_desync_total 9621
telemt_desync_full_logged_total 5373
telemt_desync_suppressed_total 4248
telemt_desync_frames_bucket_total{bucket="1_2"} 2257
telemt_desync_frames_bucket_total{bucket="3_10"} 3789
telemt_desync_frames_bucket_total{bucket="gt_10"} 3575
telemt_pool_swap_total 72
telemt_pool_force_close_total 2070
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 172
telemt_me_draining_writers_reap_progress_total 29136
telemt_me_writer_removed_unexpected_total 1524
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3218
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27443
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1824
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 246
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 27066
telemt_me_writer_teardown_success_total{mode="normal"} 30661
telemt_me_writer_teardown_noop_total 29136
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 58354
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 59269
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 59512
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 59766
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 59794
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 59797
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 59797
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 59797
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 59797
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 59797
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 59797
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 59797
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 59797
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 9.788444
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 59797
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 172
telemt_me_refill_failed_total 91
telemt_me_writer_restored_same_endpoint_total 1414
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 35
telemt_me_writer_removed_unexpected_minus_restored_total 86
telemt_user_connections_total{user="hello"} 2441748
telemt_user_connections_current{user="hello"} 2391
telemt_user_octets_from_client{user="hello"} 29452530527 (27.43 GB)
telemt_user_octets_to_client{user="hello"} 559460072986 (521.04 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 1479
telemt_user_unique_ips_recent_window{user="hello"} 577
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 148815.5 (41h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13982527
telemt_connections_bad_total 1233530
telemt_connections_current 4280
telemt_connections_me_current 4280
telemt_handshake_timeouts_total 352340
telemt_upstream_connect_attempt_total 54003
telemt_upstream_connect_success_total 53921
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 53929
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24430
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29261
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 224
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2457
telemt_me_reconnect_success_total 1281
telemt_me_reader_eof_total 1224
telemt_me_idle_close_by_peer_total 1223
telemt_me_route_drop_no_conn_total 12148444
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 11211511
telemt_me_endpoint_quarantine_total 951
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 1108
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
telemt_desync_total 45660
telemt_desync_full_logged_total 14478
telemt_desync_suppressed_total 31182
telemt_desync_frames_bucket_total{bucket="1_2"} 10349
telemt_desync_frames_bucket_total{bucket="3_10"} 17861
telemt_desync_frames_bucket_total{bucket="gt_10"} 17450
telemt_pool_swap_total 160
telemt_pool_force_close_total 5473
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 867
telemt_me_draining_writers_reap_progress_total 49252
telemt_me_writer_removed_unexpected_total 1180
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4275
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 45492
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 41
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5037
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 436
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 43779
telemt_me_writer_teardown_success_total{mode="normal"} 49767
telemt_me_writer_teardown_noop_total 49301
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 89678
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 92682
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 94146
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 96186
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 97658
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 98529
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 99038
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 99068
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 99068
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 99068
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 99068
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 99068
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 99068
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 254.340303
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 99068
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 867
telemt_me_refill_failed_total 65
telemt_me_writer_restored_same_endpoint_total 1103
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 70
telemt_user_connections_total{user="hello"} 11199240
telemt_user_connections_current{user="hello"} 4279
telemt_user_octets_from_client{user="hello"} 160929286020 (149.88 GB)
telemt_user_octets_to_client{user="hello"} 2986424615548 (2.72 TB)
telemt_user_unique_ips_current{user="hello"} 1673
telemt_user_unique_ips_recent_window{user="hello"} 748
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 148816.3 (41h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10381906
telemt_connections_bad_total 986785
telemt_connections_current 4376
telemt_connections_me_current 4376
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 310464
telemt_upstream_connect_attempt_total 80349
telemt_upstream_connect_success_total 79208
telemt_upstream_connect_fail_total 820
telemt_upstream_connect_attempts_per_request{bucket="1"} 80028
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43580
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31793
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 157
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3678
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 820
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 182
telemt_me_reconnect_attempts_total 3695
telemt_me_reconnect_success_total 1468
telemt_me_reader_eof_total 1342
telemt_me_idle_close_by_peer_total 1342
telemt_me_route_drop_no_conn_total 4123527
telemt_me_route_drop_channel_closed_total 449
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7746338
telemt_me_endpoint_quarantine_total 931
telemt_me_single_endpoint_outage_enter_total 24
telemt_me_single_endpoint_outage_exit_total 24
telemt_me_single_endpoint_outage_reconnect_attempt_total 29
telemt_me_single_endpoint_outage_reconnect_success_total 22
telemt_me_single_endpoint_quarantine_bypass_total 29
telemt_me_single_endpoint_shadow_rotate_total 1130
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
telemt_me_writers_active_current 46
telemt_desync_total 34565
telemt_desync_full_logged_total 11629
telemt_desync_suppressed_total 22936
telemt_desync_frames_bucket_total{bucket="1_2"} 8529
telemt_desync_frames_bucket_total{bucket="3_10"} 13285
telemt_desync_frames_bucket_total{bucket="gt_10"} 12751
telemt_pool_swap_total 159
telemt_pool_force_close_total 4907
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 618
telemt_me_draining_writers_reap_progress_total 47436
telemt_me_writer_removed_unexpected_total 1375
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4309
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 44358
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 15
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4484
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 423
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 42529
telemt_me_writer_teardown_success_total{mode="normal"} 48667
telemt_me_writer_teardown_noop_total 47451
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 90281
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 92997
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 94013
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 95065
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 95756
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 96057
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 96108
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 96110
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 96116
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 96118
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 96118
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 96118
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 96118
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 91.818534
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 96118
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 618
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 1245
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 116
telemt_user_connections_total{user="hello"} 7685827
telemt_user_connections_current{user="hello"} 4376
telemt_user_octets_from_client{user="hello"} 195234347509 (181.83 GB)
telemt_user_octets_to_client{user="hello"} 3466528465822 (3.15 TB)
telemt_user_msgs_from_client{user="hello"} 113340
telemt_user_msgs_to_client{user="hello"} 116189
telemt_user_unique_ips_current{user="hello"} 1762
telemt_user_unique_ips_recent_window{user="hello"} 575
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 148780.8 (41h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9830887
telemt_connections_bad_total 826085
telemt_connections_current 4208
telemt_connections_me_current 4208
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 317299
telemt_upstream_connect_attempt_total 65803
telemt_upstream_connect_success_total 64900
telemt_upstream_connect_fail_total 181
telemt_upstream_connect_attempts_per_request{bucket="1"} 65081
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31186
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30515
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1185
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2014
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 181
telemt_me_keepalive_timeout_total 1383
telemt_me_reconnect_attempts_total 4178
telemt_me_reconnect_success_total 1805
telemt_me_reader_eof_total 1572
telemt_me_idle_close_by_peer_total 1571
telemt_me_route_drop_no_conn_total 4852469
telemt_me_route_drop_channel_closed_total 330
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7423979
telemt_me_endpoint_quarantine_total 1020
telemt_me_single_endpoint_outage_enter_total 28
telemt_me_single_endpoint_outage_exit_total 28
telemt_me_single_endpoint_outage_reconnect_attempt_total 29
telemt_me_single_endpoint_outage_reconnect_success_total 23
telemt_me_single_endpoint_quarantine_bypass_total 29
telemt_me_single_endpoint_shadow_rotate_total 1091
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 54
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
telemt_desync_total 34372
telemt_desync_full_logged_total 11410
telemt_desync_suppressed_total 22962
telemt_desync_frames_bucket_total{bucket="1_2"} 8696
telemt_desync_frames_bucket_total{bucket="3_10"} 13176
telemt_desync_frames_bucket_total{bucket="gt_10"} 12500
telemt_pool_swap_total 155
telemt_pool_force_close_total 4848
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 659
telemt_me_draining_writers_reap_progress_total 48092
telemt_me_writer_removed_unexpected_total 1717
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4815
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 44907
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 21
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4333
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 515
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 43244
telemt_me_writer_teardown_success_total{mode="normal"} 49722
telemt_me_writer_teardown_noop_total 48159
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 92848
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 95213
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 96040
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 96972
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 97466
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 97646
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 97749
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 97773
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 97781
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 97794
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 97827
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 97830
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 97881
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3158.726686
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 97881
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 659
telemt_me_refill_failed_total 122
telemt_me_writer_restored_same_endpoint_total 1575
telemt_me_writer_restored_fallback_total 7
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 56
telemt_me_writer_removed_unexpected_minus_restored_total 135
telemt_user_connections_total{user="hello"} 7417876
telemt_user_connections_current{user="hello"} 4208
telemt_user_octets_from_client{user="hello"} 174117455605 (162.16 GB)
telemt_user_octets_to_client{user="hello"} 3096189177661 (2.82 TB)
telemt_user_msgs_from_client{user="hello"} 46485
telemt_user_msgs_to_client{user="hello"} 113805
telemt_user_unique_ips_current{user="hello"} 1655
telemt_user_unique_ips_recent_window{user="hello"} 619
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 19060.8 (5h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8038849
telemt_connections_bad_total 506023
telemt_connections_current 6448
telemt_connections_me_current 6448
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 128900
telemt_upstream_connect_attempt_total 28335
telemt_upstream_connect_success_total 26942
telemt_upstream_connect_fail_total 1024
telemt_upstream_connect_attempts_per_request{bucket="1"} 27966
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15063
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6608
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 543
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4728
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1024
telemt_me_keepalive_timeout_total 691
telemt_me_reconnect_attempts_total 5459
telemt_me_reconnect_success_total 539
telemt_me_reader_eof_total 325
telemt_me_idle_close_by_peer_total 325
telemt_me_route_drop_no_conn_total 19725492
telemt_me_route_drop_channel_closed_total 28
telemt_me_route_drop_queue_full_total 26
telemt_me_route_drop_queue_full_profile_total{profile="high"} 26
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6695959
telemt_me_endpoint_quarantine_total 123
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 63
telemt_me_single_endpoint_outage_reconnect_success_total 21
telemt_me_single_endpoint_quarantine_bypass_total 63
telemt_me_single_endpoint_shadow_rotate_total 148
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
telemt_me_writers_active_current 55
telemt_desync_total 9791
telemt_desync_full_logged_total 2509
telemt_desync_suppressed_total 7282
telemt_desync_frames_bucket_total{bucket="1_2"} 1743
telemt_desync_frames_bucket_total{bucket="3_10"} 3966
telemt_desync_frames_bucket_total{bucket="gt_10"} 4082
telemt_pool_swap_total 18
telemt_pool_force_close_total 715
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 259
telemt_me_draining_writers_reap_progress_total 4977
telemt_me_writer_removed_unexpected_total 455
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 870
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 4522
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 505
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 210
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 4262
telemt_me_writer_teardown_success_total{mode="normal"} 5392
telemt_me_writer_teardown_noop_total 4980
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 8464
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 9379
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 9741
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 10125
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 10295
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 10366
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 10372
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 10372
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 10372
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 10372
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 10372
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 10372
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 10372
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 22.933569
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 10372
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 259
telemt_me_refill_failed_total 284
telemt_me_writer_restored_same_endpoint_total 373
telemt_me_writer_restored_fallback_total 3
telemt_me_no_writer_failfast_total 86
telemt_me_async_recovery_trigger_total 3059
telemt_me_writer_removed_unexpected_minus_restored_total 79
telemt_user_connections_total{user="hello"} 6710968
telemt_user_connections_current{user="hello"} 6448
telemt_user_octets_from_client{user="hello"} 37630070951 (35.05 GB)
telemt_user_octets_to_client{user="hello"} 196970669636 (183.44 GB)
telemt_user_msgs_from_client{user="hello"} 37295
telemt_user_msgs_to_client{user="hello"} 32778
telemt_user_unique_ips_current{user="hello"} 2383
telemt_user_unique_ips_recent_window{user="hello"} 1147
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 148786.9 (41h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9544900
telemt_connections_bad_total 791540
telemt_connections_current 4084
telemt_connections_me_current 4084
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 206304
telemt_upstream_connect_attempt_total 90094
telemt_upstream_connect_success_total 89189
telemt_upstream_connect_fail_total 783
telemt_upstream_connect_attempts_per_request{bucket="1"} 89972
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 55271
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32458
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 208
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1252
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 783
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 71352
telemt_me_reconnect_success_total 2423
telemt_me_reader_eof_total 2153
telemt_me_idle_close_by_peer_total 2152
telemt_me_route_drop_no_conn_total 4643324
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7532498
telemt_me_endpoint_quarantine_total 1000
telemt_me_single_endpoint_outage_enter_total 33
telemt_me_single_endpoint_outage_exit_total 33
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 33
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1112
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 46
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
telemt_desync_total 38580
telemt_desync_full_logged_total 13182
telemt_desync_suppressed_total 25398
telemt_desync_frames_bucket_total{bucket="1_2"} 7833
telemt_desync_frames_bucket_total{bucket="3_10"} 14926
telemt_desync_frames_bucket_total{bucket="gt_10"} 15821
telemt_pool_swap_total 153
telemt_pool_force_close_total 4532
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 554
telemt_me_draining_writers_reap_progress_total 50717
telemt_me_writer_removed_unexpected_total 2180
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5353
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 47561
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3915
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 617
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 46185
telemt_me_writer_teardown_success_total{mode="normal"} 52914
telemt_me_writer_teardown_noop_total 50718
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 101792
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 102956
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 103322
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 103588
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 103622
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 103625
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 103625
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 103628
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 103632
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 103632
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 103632
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 103632
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 103632
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 15.830506
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 103632
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 554
telemt_me_refill_failed_total 4253
telemt_me_writer_restored_same_endpoint_total 2031
telemt_me_writer_restored_fallback_total 42
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7358
telemt_me_writer_removed_unexpected_minus_restored_total 107
telemt_user_connections_total{user="hello"} 7533568
telemt_user_connections_current{user="hello"} 4084
telemt_user_octets_from_client{user="hello"} 173574221815 (161.65 GB)
telemt_user_octets_to_client{user="hello"} 2865848522365 (2.61 TB)
telemt_user_msgs_from_client{user="hello"} 146235
telemt_user_msgs_to_client{user="hello"} 572261
telemt_user_unique_ips_current{user="hello"} 1645
telemt_user_unique_ips_recent_window{user="hello"} 794
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 85623.1 (23h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9540330
telemt_connections_bad_total 341901
telemt_connections_current 5217
telemt_connections_me_current 5217
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4011918
telemt_upstream_connect_attempt_total 42329
telemt_upstream_connect_success_total 42020
telemt_upstream_connect_fail_total 302
telemt_upstream_connect_attempts_per_request{bucket="1"} 42322
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24029
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17876
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 115
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 302
telemt_me_reconnect_attempts_total 47928
telemt_me_reconnect_success_total 1442
telemt_me_reader_eof_total 1110
telemt_me_idle_close_by_peer_total 1110
telemt_me_route_drop_no_conn_total 3485813
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4597866
telemt_me_endpoint_quarantine_total 562
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 58
telemt_me_single_endpoint_outage_reconnect_success_total 18
telemt_me_single_endpoint_quarantine_bypass_total 58
telemt_me_single_endpoint_shadow_rotate_total 643
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 21
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
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 25176
telemt_desync_full_logged_total 8437
telemt_desync_suppressed_total 16739
telemt_desync_frames_bucket_total{bucket="1_2"} 5080
telemt_desync_frames_bucket_total{bucket="3_10"} 9963
telemt_desync_frames_bucket_total{bucket="gt_10"} 10133
telemt_pool_swap_total 90
telemt_pool_force_close_total 2772
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 287
telemt_me_draining_writers_reap_progress_total 29661
telemt_me_writer_removed_unexpected_total 1175
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2684
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 28180
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2363
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 409
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26889
telemt_me_writer_teardown_success_total{mode="normal"} 30864
telemt_me_writer_teardown_noop_total 29668
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 59522
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 60088
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 60322
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 60532
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 60532
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 60532
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 60532
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 60532
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 60532
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 60532
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 60532
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 60532
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 60532
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.140318
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 60532
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 287
telemt_me_refill_failed_total 2702
telemt_me_writer_restored_same_endpoint_total 1289
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4328
telemt_user_connections_total{user="hello"} 4592402
telemt_user_connections_current{user="hello"} 5217
telemt_user_octets_from_client{user="hello"} 100648109172 (93.74 GB)
telemt_user_octets_to_client{user="hello"} 1755918050110 (1.60 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 2038
telemt_user_unique_ips_recent_window{user="hello"} 871
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 66593.5 (18h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 794920
telemt_connections_bad_total 10668
telemt_connections_current 1035
telemt_connections_me_current 1035
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 15009
telemt_upstream_connect_attempt_total 33654
telemt_upstream_connect_success_total 33570
telemt_upstream_connect_fail_total 69
telemt_upstream_connect_attempts_per_request{bucket="1"} 33639
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15376
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17769
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 425
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 69
telemt_me_reconnect_attempts_total 1517
telemt_me_reconnect_success_total 653
telemt_me_reader_eof_total 629
telemt_me_idle_close_by_peer_total 629
telemt_me_route_drop_no_conn_total 272719
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 711857
telemt_me_endpoint_quarantine_total 597
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 554
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
telemt_desync_total 3937
telemt_desync_full_logged_total 1187
telemt_desync_suppressed_total 2750
telemt_desync_frames_bucket_total{bucket="1_2"} 959
telemt_desync_frames_bucket_total{bucket="3_10"} 1571
telemt_desync_frames_bucket_total{bucket="gt_10"} 1407
telemt_pool_swap_total 70
telemt_pool_force_close_total 1738
telemt_me_writer_close_signal_drop_total 102
telemt_me_draining_writers_reap_progress_total 27657
telemt_me_writer_removed_unexpected_total 608
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2120
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26168
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1660
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 78
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 25919
telemt_me_writer_teardown_success_total{mode="normal"} 28288
telemt_me_writer_teardown_noop_total 27659
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 55384
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 55810
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 55922
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 55947
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 55947
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 55947
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 55947
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 55947
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 55947
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 55947
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 55947
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 55947
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 55947
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.037376
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 55947
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 102
telemt_me_refill_failed_total 47
telemt_me_writer_restored_same_endpoint_total 559
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 38
telemt_user_connections_total{user="hello"} 713186
telemt_user_connections_current{user="hello"} 1035
telemt_user_octets_from_client{user="hello"} 13357664717 (12.44 GB)
telemt_user_octets_to_client{user="hello"} 335741141275 (312.68 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 390
telemt_user_unique_ips_recent_window{user="hello"} 152
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 148791.3 (41h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11641589
telemt_connections_bad_total 1358159
telemt_connections_current 5680
telemt_connections_me_current 5680
telemt_handshake_timeouts_total 317550
telemt_upstream_connect_attempt_total 56072
telemt_upstream_connect_success_total 55855
telemt_upstream_connect_fail_total 169
telemt_upstream_connect_attempts_per_request{bucket="1"} 56024
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27542
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28265
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 47
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 169
telemt_me_reconnect_attempts_total 2192
telemt_me_reconnect_success_total 1168
telemt_me_reader_eof_total 1133
telemt_me_idle_close_by_peer_total 1133
telemt_me_route_drop_no_conn_total 3682695
telemt_me_route_drop_channel_closed_total 99
telemt_me_route_drop_queue_full_total 33
telemt_me_route_drop_queue_full_profile_total{profile="high"} 33
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8756546
telemt_me_endpoint_quarantine_total 1019
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 12
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 12
telemt_me_single_endpoint_shadow_rotate_total 1116
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
telemt_me_writers_active_current 47
telemt_desync_total 36045
telemt_desync_full_logged_total 11798
telemt_desync_suppressed_total 24247
telemt_desync_frames_bucket_total{bucket="1_2"} 8590
telemt_desync_frames_bucket_total{bucket="3_10"} 13346
telemt_desync_frames_bucket_total{bucket="gt_10"} 14109
telemt_pool_swap_total 165
telemt_pool_force_close_total 4546
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 571
telemt_me_draining_writers_reap_progress_total 50526
telemt_me_writer_removed_unexpected_total 1088
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4147
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 47497
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4390
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 156
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 45980
telemt_me_writer_teardown_success_total{mode="normal"} 51644
telemt_me_writer_teardown_noop_total 50528
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 100010
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 101456
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 101762
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 102051
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 102159
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 102172
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 102172
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 102172
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 102172
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 102172
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 102172
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 102172
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 102172
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 16.507531
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 102172
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 571
telemt_me_refill_failed_total 53
telemt_me_writer_restored_same_endpoint_total 1024
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 8726905
telemt_user_connections_current{user="hello"} 5680
telemt_user_octets_from_client{user="hello"} 168483529504 (156.91 GB)
telemt_user_octets_to_client{user="hello"} 3931170121960 (3.58 TB)
telemt_user_unique_ips_current{user="hello"} 2077
telemt_user_unique_ips_recent_window{user="hello"} 724
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 148788.0 (41h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10061736
telemt_connections_bad_total 1128438
telemt_connections_current 4496
telemt_connections_me_current 4496
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 263393
telemt_upstream_connect_attempt_total 81699
telemt_upstream_connect_success_total 81096
telemt_upstream_connect_fail_total 522
telemt_upstream_connect_attempts_per_request{bucket="1"} 81618
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44849
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33330
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 909
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2008
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 522
telemt_me_reconnect_attempts_total 8595
telemt_me_reconnect_success_total 1948
telemt_me_reader_eof_total 1814
telemt_me_idle_close_by_peer_total 1814
telemt_me_seq_mismatch_total 72
telemt_me_route_drop_no_conn_total 4560774
telemt_me_route_drop_channel_closed_total 321
telemt_me_route_drop_queue_full_total 17
telemt_me_route_drop_queue_full_profile_total{profile="high"} 17
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7748540
telemt_me_endpoint_quarantine_total 1140
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 35
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 1119
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 46
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
telemt_desync_total 35173
telemt_desync_full_logged_total 11454
telemt_desync_suppressed_total 23719
telemt_desync_frames_bucket_total{bucket="1_2"} 8671
telemt_desync_frames_bucket_total{bucket="3_10"} 13094
telemt_desync_frames_bucket_total{bucket="gt_10"} 13408
telemt_pool_swap_total 158
telemt_pool_force_close_total 4407
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 569
telemt_me_draining_writers_reap_progress_total 49880
telemt_me_writer_removed_unexpected_total 1839
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5174
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 46612
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4003
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 404
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 45473
telemt_me_writer_teardown_success_total{mode="normal"} 51786
telemt_me_writer_teardown_noop_total 49884
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 99315
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 100860
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 101342
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 101620
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 101670
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 101670
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 101670
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 101670
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 101670
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 101670
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 101670
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 101670
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 101670
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 15.400311
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 101670
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 569
telemt_me_refill_failed_total 341
telemt_me_writer_restored_same_endpoint_total 1580
telemt_me_writer_restored_fallback_total 98
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 128
telemt_me_writer_removed_unexpected_minus_restored_total 161
telemt_user_connections_total{user="hello"} 7755410
telemt_user_connections_current{user="hello"} 4497
telemt_user_octets_from_client{user="hello"} 136708487241 (127.32 GB)
telemt_user_octets_to_client{user="hello"} 3045768536503 (2.77 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 1724
telemt_user_unique_ips_recent_window{user="hello"} 645
```