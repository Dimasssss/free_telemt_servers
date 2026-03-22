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

# Server Metrics 2026-03-22 00:43:44 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 13042.1 (3h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 195751
telemt_connections_bad_total 13534
telemt_connections_current 659
telemt_connections_me_current 659
telemt_handshake_timeouts_total 11111
telemt_upstream_connect_attempt_total 5375
telemt_upstream_connect_success_total 5374
telemt_upstream_connect_attempts_per_request{bucket="1"} 5374
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1987
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3373
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 180
telemt_me_reconnect_success_total 91
telemt_me_reader_eof_total 88
telemt_me_idle_close_by_peer_total 88
telemt_me_route_drop_no_conn_total 37943
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 159645
telemt_me_endpoint_quarantine_total 93
telemt_me_single_endpoint_shadow_rotate_total 113
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
telemt_me_writers_active_current 43
telemt_desync_total 1208
telemt_desync_full_logged_total 339
telemt_desync_suppressed_total 869
telemt_desync_frames_bucket_total{bucket="1_2"} 338
telemt_desync_frames_bucket_total{bucket="3_10"} 417
telemt_desync_frames_bucket_total{bucket="gt_10"} 453
telemt_pool_swap_total 14
telemt_pool_force_close_total 374
telemt_me_writer_close_signal_drop_total 24
telemt_me_draining_writers_reap_progress_total 4804
telemt_me_writer_removed_unexpected_total 88
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 361
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 4519
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 370
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 4430
telemt_me_writer_teardown_success_total{mode="normal"} 4880
telemt_me_writer_teardown_noop_total 4805
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 9378
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 9560
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 9614
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 9659
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 9683
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 9685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 9685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 9685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 9685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 9685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 9685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 9685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 9685
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.699115
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 9685
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 24
telemt_me_refill_failed_total 5
telemt_me_writer_restored_same_endpoint_total 83
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 159389
telemt_user_connections_current{user="hello"} 659
telemt_user_octets_from_client{user="hello"} 1798766688 (1.68 GB)
telemt_user_octets_to_client{user="hello"} 54508970800 (50.77 GB)
telemt_user_unique_ips_current{user="hello"} 304
telemt_user_unique_ips_recent_window{user="hello"} 74
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 26408.4 (7h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 702977
telemt_connections_bad_total 40598
telemt_connections_current 339
telemt_connections_me_current 339
telemt_handshake_timeouts_total 26643
telemt_upstream_connect_attempt_total 11479
telemt_upstream_connect_success_total 11282
telemt_upstream_connect_fail_total 178
telemt_upstream_connect_attempts_per_request{bucket="1"} 11460
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5066
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6179
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 178
telemt_me_reconnect_attempts_total 1022
telemt_me_reconnect_success_total 343
telemt_me_reader_eof_total 297
telemt_me_idle_close_by_peer_total 297
telemt_me_route_drop_no_conn_total 330658
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 568046
telemt_me_endpoint_quarantine_total 242
telemt_me_single_endpoint_outage_enter_total 15
telemt_me_single_endpoint_outage_exit_total 15
telemt_me_single_endpoint_outage_reconnect_attempt_total 15
telemt_me_single_endpoint_outage_reconnect_success_total 15
telemt_me_single_endpoint_quarantine_bypass_total 15
telemt_me_single_endpoint_shadow_rotate_total 216
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 16
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
telemt_me_writers_active_current 48
telemt_desync_total 2465
telemt_desync_full_logged_total 1420
telemt_desync_suppressed_total 1045
telemt_desync_frames_bucket_total{bucket="1_2"} 526
telemt_desync_frames_bucket_total{bucket="3_10"} 924
telemt_desync_frames_bucket_total{bucket="gt_10"} 1015
telemt_pool_swap_total 29
telemt_pool_force_close_total 794
telemt_me_writer_close_signal_drop_total 58
telemt_me_draining_writers_reap_progress_total 10112
telemt_me_writer_removed_unexpected_total 280
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 882
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 9514
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 787
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 9318
telemt_me_writer_teardown_success_total{mode="normal"} 10396
telemt_me_writer_teardown_noop_total 10112
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 20046
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 20316
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 20402
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 20494
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 20506
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 20508
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 20508
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 20508
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 20508
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 20508
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 20508
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 20508
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 20508
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.403041
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 20508
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 58
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 238
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 567201
telemt_user_connections_current{user="hello"} 339
telemt_user_octets_from_client{user="hello"} 9620802132 (8.96 GB)
telemt_user_octets_to_client{user="hello"} 200340410412 (186.58 GB)
telemt_user_unique_ips_current{user="hello"} 245
telemt_user_unique_ips_recent_window{user="hello"} 99
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 101268.2 (28h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7529328
telemt_connections_bad_total 608270
telemt_connections_current 1436
telemt_connections_me_current 1436
telemt_handshake_timeouts_total 245171
telemt_upstream_connect_attempt_total 36893
telemt_upstream_connect_success_total 36821
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 36828
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16670
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19985
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 160
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1521
telemt_me_reconnect_success_total 759
telemt_me_reader_eof_total 770
telemt_me_idle_close_by_peer_total 770
telemt_me_route_drop_no_conn_total 4509183
telemt_me_route_drop_channel_closed_total 66
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6126680
telemt_me_endpoint_quarantine_total 642
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 754
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 24
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
telemt_desync_total 26007
telemt_desync_full_logged_total 8601
telemt_desync_suppressed_total 17406
telemt_desync_frames_bucket_total{bucket="1_2"} 5597
telemt_desync_frames_bucket_total{bucket="3_10"} 10141
telemt_desync_frames_bucket_total{bucket="gt_10"} 10269
telemt_pool_swap_total 109
telemt_pool_force_close_total 3662
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 581
telemt_me_draining_writers_reap_progress_total 33650
telemt_me_writer_removed_unexpected_total 740
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2835
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 31114
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3423
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 239
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 29988
telemt_me_writer_teardown_success_total{mode="normal"} 33949
telemt_me_writer_teardown_noop_total 33694
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 61637
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 63422
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 64380
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 65826
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 66803
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 67342
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 67632
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 67643
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 67643
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 67643
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 67643
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 67643
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 67643
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 155.484119
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 67643
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 581
telemt_me_refill_failed_total 40
telemt_me_writer_restored_same_endpoint_total 676
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 59
telemt_user_connections_total{user="hello"} 6118982
telemt_user_connections_current{user="hello"} 1436
telemt_user_octets_from_client{user="hello"} 104947259444 (97.74 GB)
telemt_user_octets_to_client{user="hello"} 2022448246412 (1.84 TB)
telemt_user_unique_ips_current{user="hello"} 758
telemt_user_unique_ips_recent_window{user="hello"} 137
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 101269.6 (28h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6195675
telemt_connections_bad_total 580715
telemt_connections_current 1380
telemt_connections_me_current 1380
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 205066
telemt_upstream_connect_attempt_total 41086
telemt_upstream_connect_success_total 40703
telemt_upstream_connect_fail_total 186
telemt_upstream_connect_attempts_per_request{bucket="1"} 40889
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20324
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19791
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 555
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 186
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 1857
telemt_me_reconnect_success_total 821
telemt_me_reader_eof_total 794
telemt_me_idle_close_by_peer_total 794
telemt_me_route_drop_no_conn_total 2207778
telemt_me_route_drop_channel_closed_total 255
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4643732
telemt_me_endpoint_quarantine_total 619
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 776
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 29
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
telemt_desync_total 22208
telemt_desync_full_logged_total 7530
telemt_desync_suppressed_total 14678
telemt_desync_frames_bucket_total{bucket="1_2"} 5351
telemt_desync_frames_bucket_total{bucket="3_10"} 8609
telemt_desync_frames_bucket_total{bucket="gt_10"} 8248
telemt_pool_swap_total 110
telemt_pool_force_close_total 3314
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 350
telemt_me_draining_writers_reap_progress_total 32376
telemt_me_writer_removed_unexpected_total 776
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2758
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 30329
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3101
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 213
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 29062
telemt_me_writer_teardown_success_total{mode="normal"} 33087
telemt_me_writer_teardown_noop_total 32382
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 62188
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 63707
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 64276
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 64853
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 65264
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 65449
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 65469
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 65469
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 65469
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 65469
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 65469
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 65469
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 65469
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 48.175889
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 65469
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 350
telemt_me_refill_failed_total 55
telemt_me_writer_restored_same_endpoint_total 714
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 54
telemt_user_connections_total{user="hello"} 4577970
telemt_user_connections_current{user="hello"} 1380
telemt_user_octets_from_client{user="hello"} 138727347033 (129.20 GB)
telemt_user_octets_to_client{user="hello"} 2148733650391 (1.95 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 709
telemt_user_unique_ips_recent_window{user="hello"} 113
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 101233.7 (28h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6101250
telemt_connections_bad_total 541839
telemt_connections_current 1332
telemt_connections_me_current 1332
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 195706
telemt_upstream_connect_attempt_total 47385
telemt_upstream_connect_success_total 47059
telemt_upstream_connect_fail_total 136
telemt_upstream_connect_attempts_per_request{bucket="1"} 47195
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24448
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21171
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 387
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1053
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 136
telemt_me_keepalive_timeout_total 58
telemt_me_reconnect_attempts_total 1843
telemt_me_reconnect_success_total 856
telemt_me_reader_eof_total 799
telemt_me_idle_close_by_peer_total 799
telemt_me_route_drop_no_conn_total 2115071
telemt_me_route_drop_channel_closed_total 111
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4549848
telemt_me_endpoint_quarantine_total 692
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 758
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 36
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
telemt_me_writers_active_current 48
telemt_desync_total 22076
telemt_desync_full_logged_total 7374
telemt_desync_suppressed_total 14702
telemt_desync_frames_bucket_total{bucket="1_2"} 5394
telemt_desync_frames_bucket_total{bucket="3_10"} 8455
telemt_desync_frames_bucket_total{bucket="gt_10"} 8227
telemt_pool_swap_total 109
telemt_pool_force_close_total 3197
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 372
telemt_me_draining_writers_reap_progress_total 33709
telemt_me_writer_removed_unexpected_total 767
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2818
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 31669
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2982
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 215
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 30512
telemt_me_writer_teardown_success_total{mode="normal"} 34487
telemt_me_writer_teardown_noop_total 33720
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 65720
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 67070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 67500
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 67957
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 68164
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 68189
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 68207
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 68207
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 68207
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 68207
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 68207
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 68207
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 68207
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 25.560864
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 68207
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 372
telemt_me_refill_failed_total 54
telemt_me_writer_restored_same_endpoint_total 742
telemt_me_writer_restored_fallback_total 5
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 4550752
telemt_user_connections_current{user="hello"} 1332
telemt_user_octets_from_client{user="hello"} 132202000615 (123.12 GB)
telemt_user_octets_to_client{user="hello"} 2081054414979 (1.89 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 683
telemt_user_unique_ips_recent_window{user="hello"} 141
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 101273.0 (28h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20102890
telemt_connections_bad_total 1516412
telemt_connections_current 2037
telemt_connections_me_current 2037
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 584663
telemt_upstream_connect_attempt_total 190300
telemt_upstream_connect_success_total 172628
telemt_upstream_connect_fail_total 16044
telemt_upstream_connect_attempts_per_request{bucket="1"} 188672
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 121875
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 40643
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1221
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8889
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16044
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 64393
telemt_me_reconnect_success_total 2192
telemt_me_reader_eof_total 1375
telemt_me_idle_close_by_peer_total 1374
telemt_me_route_drop_no_conn_total 39468072
telemt_me_route_drop_channel_closed_total 122
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16331513
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 779
telemt_me_single_endpoint_outage_enter_total 124
telemt_me_single_endpoint_outage_exit_total 124
telemt_me_single_endpoint_outage_reconnect_attempt_total 260
telemt_me_single_endpoint_outage_reconnect_success_total 63
telemt_me_single_endpoint_quarantine_bypass_total 260
telemt_me_single_endpoint_shadow_rotate_total 791
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
telemt_desync_total 31556
telemt_desync_full_logged_total 9409
telemt_desync_suppressed_total 22147
telemt_desync_frames_bucket_total{bucket="1_2"} 6861
telemt_desync_frames_bucket_total{bucket="3_10"} 13990
telemt_desync_frames_bucket_total{bucket="gt_10"} 10705
telemt_pool_swap_total 104
telemt_pool_force_close_total 3441
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 767
telemt_me_draining_writers_reap_progress_total 31521
telemt_me_writer_removed_unexpected_total 2034
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4288
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 29003
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2919
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 522
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 28080
telemt_me_writer_teardown_success_total{mode="normal"} 33291
telemt_me_writer_teardown_noop_total 31547
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 58261
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 60624
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 61875
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 63474
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 64402
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 64737
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 64819
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 64821
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 64824
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 64829
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 64829
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 64833
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 64838
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 212.406535
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 64838
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 767
telemt_me_refill_failed_total 3789
telemt_me_writer_restored_same_endpoint_total 1521
telemt_me_writer_restored_fallback_total 21
telemt_me_no_writer_failfast_total 666
telemt_me_async_recovery_trigger_total 14678
telemt_me_writer_removed_unexpected_minus_restored_total 492
telemt_user_connections_total{user="hello"} 16459138
telemt_user_connections_current{user="hello"} 2037
telemt_user_octets_from_client{user="hello"} 195263810248 (181.85 GB)
telemt_user_octets_to_client{user="hello"} 1147375170606 (1.04 TB)
telemt_user_msgs_from_client{user="hello"} 367794
telemt_user_msgs_to_client{user="hello"} 650852
telemt_user_unique_ips_current{user="hello"} 966
telemt_user_unique_ips_recent_window{user="hello"} 238
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 101240.5 (28h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5884442
telemt_connections_bad_total 554407
telemt_connections_current 1622
telemt_connections_me_current 1622
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 122398
telemt_upstream_connect_attempt_total 55552
telemt_upstream_connect_success_total 54897
telemt_upstream_connect_fail_total 562
telemt_upstream_connect_attempts_per_request{bucket="1"} 55459
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32507
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22048
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 341
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 562
telemt_me_reconnect_attempts_total 69415
telemt_me_reconnect_success_total 1727
telemt_me_reader_eof_total 1499
telemt_me_idle_close_by_peer_total 1498
telemt_me_route_drop_no_conn_total 2366966
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4588070
telemt_me_endpoint_quarantine_total 679
telemt_me_single_endpoint_outage_enter_total 23
telemt_me_single_endpoint_outage_exit_total 23
telemt_me_single_endpoint_outage_reconnect_attempt_total 24
telemt_me_single_endpoint_outage_reconnect_success_total 23
telemt_me_single_endpoint_quarantine_bypass_total 24
telemt_me_single_endpoint_shadow_rotate_total 763
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 32
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
telemt_me_writers_active_current 48
telemt_desync_total 23077
telemt_desync_full_logged_total 8095
telemt_desync_suppressed_total 14982
telemt_desync_frames_bucket_total{bucket="1_2"} 4385
telemt_desync_frames_bucket_total{bucket="3_10"} 8934
telemt_desync_frames_bucket_total{bucket="gt_10"} 9758
telemt_pool_swap_total 104
telemt_pool_force_close_total 3044
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 383
telemt_me_draining_writers_reap_progress_total 35098
telemt_me_writer_removed_unexpected_total 1543
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3710
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 32956
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2643
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 401
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 32054
telemt_me_writer_teardown_success_total{mode="normal"} 36666
telemt_me_writer_teardown_noop_total 35099
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 70525
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 71338
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 71613
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 71733
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 71762
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 71765
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 71765
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 71765
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 71765
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 71765
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 71765
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 71765
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 71765
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.023416
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 71765
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 383
telemt_me_refill_failed_total 4196
telemt_me_writer_restored_same_endpoint_total 1449
telemt_me_writer_restored_fallback_total 32
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7305
telemt_me_writer_removed_unexpected_minus_restored_total 62
telemt_user_connections_total{user="hello"} 4581087
telemt_user_connections_current{user="hello"} 1622
telemt_user_octets_from_client{user="hello"} 122709046280 (114.28 GB)
telemt_user_octets_to_client{user="hello"} 1873048291782 (1.70 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 768
telemt_user_unique_ips_recent_window{user="hello"} 135
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 38076.4 (10h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3765733
telemt_connections_bad_total 135067
telemt_connections_current 909
telemt_connections_me_current 909
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 1557815
telemt_upstream_connect_attempt_total 23834
telemt_upstream_connect_success_total 23681
telemt_upstream_connect_fail_total 146
telemt_upstream_connect_attempts_per_request{bucket="1"} 23827
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15574
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8039
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 68
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 146
telemt_me_reconnect_attempts_total 45672
telemt_me_reconnect_success_total 906
telemt_me_reader_eof_total 582
telemt_me_idle_close_by_peer_total 582
telemt_me_route_drop_no_conn_total 1004024
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1827710
telemt_me_endpoint_quarantine_total 277
telemt_me_single_endpoint_outage_enter_total 10
telemt_me_single_endpoint_outage_exit_total 10
telemt_me_single_endpoint_outage_reconnect_attempt_total 49
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 49
telemt_me_single_endpoint_shadow_rotate_total 291
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
telemt_me_writers_active_current 45
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 10115
telemt_desync_full_logged_total 3470
telemt_desync_suppressed_total 6645
telemt_desync_frames_bucket_total{bucket="1_2"} 1795
telemt_desync_frames_bucket_total{bucket="3_10"} 3871
telemt_desync_frames_bucket_total{bucket="gt_10"} 4449
telemt_pool_swap_total 41
telemt_pool_force_close_total 1321
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 126
telemt_me_draining_writers_reap_progress_total 13200
telemt_me_writer_removed_unexpected_total 661
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1360
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 12522
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1115
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 206
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 11879
telemt_me_writer_teardown_success_total{mode="normal"} 13882
telemt_me_writer_teardown_noop_total 13202
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 26590
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 26864
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 26978
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 27084
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 27084
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 27084
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 27084
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 27084
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 27084
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 27084
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 27084
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 27084
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 27084
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.295231
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 27084
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 126
telemt_me_refill_failed_total 2601
telemt_me_writer_restored_same_endpoint_total 813
telemt_me_writer_restored_fallback_total 11
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4264
telemt_user_connections_total{user="hello"} 1831428
telemt_user_connections_current{user="hello"} 909
telemt_user_octets_from_client{user="hello"} 53085655352 (49.44 GB)
telemt_user_octets_to_client{user="hello"} 785823444214 (731.86 GB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 493
telemt_user_unique_ips_recent_window{user="hello"} 133
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 19047.5 (5h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 170224
telemt_connections_bad_total 1421
telemt_connections_current 279
telemt_connections_me_current 279
telemt_handshake_timeouts_total 4707
telemt_upstream_connect_attempt_total 8910
telemt_upstream_connect_success_total 8887
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 8908
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3815
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5001
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 71
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_reconnect_attempts_total 181
telemt_me_reconnect_success_total 118
telemt_me_reader_eof_total 119
telemt_me_idle_close_by_peer_total 119
telemt_me_route_drop_no_conn_total 47565
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 149606
telemt_me_endpoint_quarantine_total 189
telemt_me_single_endpoint_shadow_rotate_total 168
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 3
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
telemt_desync_total 994
telemt_desync_full_logged_total 248
telemt_desync_suppressed_total 746
telemt_desync_frames_bucket_total{bucket="1_2"} 388
telemt_desync_frames_bucket_total{bucket="3_10"} 363
telemt_desync_frames_bucket_total{bucket="gt_10"} 243
telemt_pool_swap_total 21
telemt_pool_force_close_total 459
telemt_me_writer_close_signal_drop_total 20
telemt_me_draining_writers_reap_progress_total 7987
telemt_me_writer_removed_unexpected_total 116
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 533
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 7573
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 457
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 7528
telemt_me_writer_teardown_success_total{mode="normal"} 8106
telemt_me_writer_teardown_noop_total 7987
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 15942
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 16065
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 16083
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 16093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 16093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 16093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 16093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 16093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 16093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 16093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 16093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 16093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 16093
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.823834
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 16093
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 20
telemt_me_refill_failed_total 4
telemt_me_writer_restored_same_endpoint_total 110
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 149320
telemt_user_connections_current{user="hello"} 279
telemt_user_octets_from_client{user="hello"} 2802472884 (2.61 GB)
telemt_user_octets_to_client{user="hello"} 86418963636 (80.48 GB)
telemt_user_unique_ips_current{user="hello"} 145
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 101244.9 (28h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7109008
telemt_connections_bad_total 720689
telemt_connections_current 1615
telemt_connections_me_current 1615
telemt_handshake_timeouts_total 202797
telemt_upstream_connect_attempt_total 39042
telemt_upstream_connect_success_total 38893
telemt_upstream_connect_fail_total 112
telemt_upstream_connect_attempts_per_request{bucket="1"} 39005
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19302
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19550
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 112
telemt_me_reconnect_attempts_total 1519
telemt_me_reconnect_success_total 804
telemt_me_reader_eof_total 786
telemt_me_idle_close_by_peer_total 786
telemt_me_route_drop_no_conn_total 2105232
telemt_me_route_drop_channel_closed_total 52
telemt_me_route_drop_queue_full_total 23
telemt_me_route_drop_queue_full_profile_total{profile="high"} 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5357241
telemt_me_endpoint_quarantine_total 699
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 778
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
telemt_me_writers_active_current 45
telemt_desync_total 20719
telemt_desync_full_logged_total 6924
telemt_desync_suppressed_total 13795
telemt_desync_frames_bucket_total{bucket="1_2"} 5036
telemt_desync_frames_bucket_total{bucket="3_10"} 7511
telemt_desync_frames_bucket_total{bucket="gt_10"} 8172
telemt_pool_swap_total 112
telemt_pool_force_close_total 3041
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 375
telemt_me_draining_writers_reap_progress_total 35162
telemt_me_writer_removed_unexpected_total 758
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2828
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 33110
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2953
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 32121
telemt_me_writer_teardown_success_total{mode="normal"} 35938
telemt_me_writer_teardown_noop_total 35164
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 69754
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 70636
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 70814
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 71014
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 71102
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 71102
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 71102
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 71102
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 71102
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 71102
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 71102
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 71102
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 71102
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.584147
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 71102
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 375
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 716
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 5332369
telemt_user_connections_current{user="hello"} 1615
telemt_user_octets_from_client{user="hello"} 108159891620 (100.73 GB)
telemt_user_octets_to_client{user="hello"} 2500390388912 (2.27 TB)
telemt_user_unique_ips_current{user="hello"} 754
telemt_user_unique_ips_recent_window{user="hello"} 132
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 101241.6 (28h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6110201
telemt_connections_bad_total 601469
telemt_connections_current 1538
telemt_connections_me_current 1538
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 168744
telemt_upstream_connect_attempt_total 54886
telemt_upstream_connect_success_total 54470
telemt_upstream_connect_fail_total 357
telemt_upstream_connect_attempts_per_request{bucket="1"} 54827
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32108
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21229
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 615
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 357
telemt_me_reconnect_attempts_total 5422
telemt_me_reconnect_success_total 1112
telemt_me_reader_eof_total 996
telemt_me_idle_close_by_peer_total 996
telemt_me_seq_mismatch_total 42
telemt_me_route_drop_no_conn_total 2158955
telemt_me_route_drop_channel_closed_total 189
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4727868
telemt_me_endpoint_quarantine_total 809
telemt_me_single_endpoint_outage_enter_total 27
telemt_me_single_endpoint_outage_exit_total 27
telemt_me_single_endpoint_outage_reconnect_attempt_total 27
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 27
telemt_me_single_endpoint_shadow_rotate_total 773
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
telemt_me_writers_active_current 45
telemt_desync_total 19475
telemt_desync_full_logged_total 6554
telemt_desync_suppressed_total 12921
telemt_desync_frames_bucket_total{bucket="1_2"} 4887
telemt_desync_frames_bucket_total{bucket="3_10"} 7081
telemt_desync_frames_bucket_total{bucket="gt_10"} 7507
telemt_pool_swap_total 110
telemt_pool_force_close_total 3001
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 371
telemt_me_draining_writers_reap_progress_total 33774
telemt_me_writer_removed_unexpected_total 1006
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3314
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 31513
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2778
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 223
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 30773
telemt_me_writer_teardown_success_total{mode="normal"} 34827
telemt_me_writer_teardown_noop_total 33778
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 66984
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 68027
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 68372
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 68567
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 68605
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 68605
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 68605
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 68605
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 68605
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 68605
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 68605
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 68605
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 68605
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.960854
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 68605
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 371
telemt_me_refill_failed_total 249
telemt_me_writer_restored_same_endpoint_total 866
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 76
telemt_me_writer_removed_unexpected_minus_restored_total 85
telemt_user_connections_total{user="hello"} 4731061
telemt_user_connections_current{user="hello"} 1538
telemt_user_octets_from_client{user="hello"} 89395140053 (83.26 GB)
telemt_user_octets_to_client{user="hello"} 2028345310732 (1.84 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 688
telemt_user_unique_ips_recent_window{user="hello"} 122
```