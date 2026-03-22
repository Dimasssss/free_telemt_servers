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

# Server Metrics 2026-03-22 01:04:04 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 14261.9 (3h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 210680
telemt_connections_bad_total 14741
telemt_connections_current 632
telemt_connections_me_current 632
telemt_handshake_timeouts_total 12099
telemt_upstream_connect_attempt_total 5888
telemt_upstream_connect_success_total 5887
telemt_upstream_connect_attempts_per_request{bucket="1"} 5887
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2154
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3719
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 209
telemt_me_reconnect_success_total 101
telemt_me_reader_eof_total 97
telemt_me_idle_close_by_peer_total 97
telemt_me_route_drop_no_conn_total 40100
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 171809
telemt_me_endpoint_quarantine_total 105
telemt_me_single_endpoint_shadow_rotate_total 121
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 35
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_desync_total 1381
telemt_desync_full_logged_total 381
telemt_desync_suppressed_total 1000
telemt_desync_frames_bucket_total{bucket="1_2"} 412
telemt_desync_frames_bucket_total{bucket="3_10"} 493
telemt_desync_frames_bucket_total{bucket="gt_10"} 476
telemt_pool_swap_total 15
telemt_pool_force_close_total 396
telemt_me_writer_close_signal_drop_total 28
telemt_me_draining_writers_reap_progress_total 5249
telemt_me_writer_removed_unexpected_total 99
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 386
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 4950
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 392
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 4853
telemt_me_writer_teardown_success_total{mode="normal"} 5336
telemt_me_writer_teardown_noop_total 5250
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 10256
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 10452
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 10515
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 10560
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 10584
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 10586
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 10586
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 10586
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 10586
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 10586
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 10586
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 10586
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 10586
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.820907
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 10586
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 28
telemt_me_refill_failed_total 6
telemt_me_writer_restored_same_endpoint_total 93
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 171539
telemt_user_connections_current{user="hello"} 632
telemt_user_octets_from_client{user="hello"} 1925630468 (1.79 GB)
telemt_user_octets_to_client{user="hello"} 57327517180 (53.39 GB)
telemt_user_unique_ips_current{user="hello"} 307
telemt_user_unique_ips_recent_window{user="hello"} 81
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 27628.2 (7h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 718522
telemt_connections_bad_total 41186
telemt_connections_current 656
telemt_connections_me_current 656
telemt_handshake_timeouts_total 27043
telemt_upstream_connect_attempt_total 12111
telemt_upstream_connect_success_total 11907
telemt_upstream_connect_fail_total 184
telemt_upstream_connect_attempts_per_request{bucket="1"} 12091
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5330
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6539
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 184
telemt_me_reconnect_attempts_total 1075
telemt_me_reconnect_success_total 354
telemt_me_reader_eof_total 308
telemt_me_idle_close_by_peer_total 308
telemt_me_route_drop_no_conn_total 332369
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 578478
telemt_me_endpoint_quarantine_total 256
telemt_me_single_endpoint_outage_enter_total 16
telemt_me_single_endpoint_outage_exit_total 16
telemt_me_single_endpoint_outage_reconnect_attempt_total 16
telemt_me_single_endpoint_outage_reconnect_success_total 16
telemt_me_single_endpoint_quarantine_bypass_total 16
telemt_me_single_endpoint_shadow_rotate_total 224
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 35
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 41
telemt_desync_total 2526
telemt_desync_full_logged_total 1446
telemt_desync_suppressed_total 1080
telemt_desync_frames_bucket_total{bucket="1_2"} 543
telemt_desync_frames_bucket_total{bucket="3_10"} 943
telemt_desync_frames_bucket_total{bucket="gt_10"} 1040
telemt_pool_swap_total 30
telemt_pool_force_close_total 821
telemt_me_writer_close_signal_drop_total 59
telemt_me_draining_writers_reap_progress_total 10696
telemt_me_writer_removed_unexpected_total 290
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 910
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 10081
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 814
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 9875
telemt_me_writer_teardown_success_total{mode="normal"} 10991
telemt_me_writer_teardown_noop_total 10696
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 21213
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 21493
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 21581
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 21673
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 21685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 21687
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 21687
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 21687
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 21687
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 21687
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 21687
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 21687
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 21687
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.458912
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 21687
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 59
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 246
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 577623
telemt_user_connections_current{user="hello"} 656
telemt_user_octets_from_client{user="hello"} 9735265008 (9.07 GB)
telemt_user_octets_to_client{user="hello"} 204019647868 (190.01 GB)
telemt_user_unique_ips_current{user="hello"} 424
telemt_user_unique_ips_recent_window{user="hello"} 198
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 102488.1 (28h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7563631
telemt_connections_bad_total 612248
telemt_connections_current 1778
telemt_connections_me_current 1778
telemt_handshake_timeouts_total 246655
telemt_upstream_connect_attempt_total 37472
telemt_upstream_connect_success_total 37400
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 37407
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16916
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20316
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 162
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1533
telemt_me_reconnect_success_total 769
telemt_me_reader_eof_total 780
telemt_me_idle_close_by_peer_total 780
telemt_me_route_drop_no_conn_total 4513322
telemt_me_route_drop_channel_closed_total 66
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6151115
telemt_me_endpoint_quarantine_total 650
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 763
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 24
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
telemt_desync_total 26106
telemt_desync_full_logged_total 8626
telemt_desync_suppressed_total 17480
telemt_desync_frames_bucket_total{bucket="1_2"} 5614
telemt_desync_frames_bucket_total{bucket="3_10"} 10186
telemt_desync_frames_bucket_total{bucket="gt_10"} 10306
telemt_pool_swap_total 110
telemt_pool_force_close_total 3688
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 582
telemt_me_draining_writers_reap_progress_total 34164
telemt_me_writer_removed_unexpected_total 750
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2872
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 31601
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3449
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 239
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 30476
telemt_me_writer_teardown_success_total{mode="normal"} 34473
telemt_me_writer_teardown_noop_total 34208
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 62664
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 64456
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 65417
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 66864
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 67841
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 68380
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 68670
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 68681
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 68681
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 68681
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 68681
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 68681
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 68681
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 155.545864
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 68681
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 582
telemt_me_refill_failed_total 40
telemt_me_writer_restored_same_endpoint_total 686
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 59
telemt_user_connections_total{user="hello"} 6143400
telemt_user_connections_current{user="hello"} 1778
telemt_user_octets_from_client{user="hello"} 105306977480 (98.07 GB)
telemt_user_octets_to_client{user="hello"} 2034328122724 (1.85 TB)
telemt_user_unique_ips_current{user="hello"} 889
telemt_user_unique_ips_recent_window{user="hello"} 278
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 102489.5 (28h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6227008
telemt_connections_bad_total 581585
telemt_connections_current 1485
telemt_connections_me_current 1485
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 206698
telemt_upstream_connect_attempt_total 41579
telemt_upstream_connect_success_total 41196
telemt_upstream_connect_fail_total 186
telemt_upstream_connect_attempts_per_request{bucket="1"} 41382
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20534
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20074
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 555
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 186
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 1887
telemt_me_reconnect_success_total 835
telemt_me_reader_eof_total 804
telemt_me_idle_close_by_peer_total 804
telemt_me_route_drop_no_conn_total 2216098
telemt_me_route_drop_channel_closed_total 255
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4666183
telemt_me_endpoint_quarantine_total 628
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 783
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
telemt_me_writers_active_current 44
telemt_desync_total 22274
telemt_desync_full_logged_total 7557
telemt_desync_suppressed_total 14717
telemt_desync_frames_bucket_total{bucket="1_2"} 5367
telemt_desync_frames_bucket_total{bucket="3_10"} 8635
telemt_desync_frames_bucket_total{bucket="gt_10"} 8272
telemt_pool_swap_total 111
telemt_pool_force_close_total 3343
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 352
telemt_me_draining_writers_reap_progress_total 32815
telemt_me_writer_removed_unexpected_total 790
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2791
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 30750
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3130
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 213
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 29472
telemt_me_writer_teardown_success_total{mode="normal"} 33541
telemt_me_writer_teardown_noop_total 32821
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 63078
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 64600
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 65169
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 65746
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 66157
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 66342
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 66362
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 66362
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 66362
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 66362
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 66362
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 66362
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 66362
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 48.191896
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 66362
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 352
telemt_me_refill_failed_total 56
telemt_me_writer_restored_same_endpoint_total 727
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 4598439
telemt_user_connections_current{user="hello"} 1485
telemt_user_octets_from_client{user="hello"} 139008483873 (129.46 GB)
telemt_user_octets_to_client{user="hello"} 2158558397803 (1.96 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 725
telemt_user_unique_ips_recent_window{user="hello"} 143
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 102453.6 (28h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6127259
telemt_connections_bad_total 542388
telemt_connections_current 1384
telemt_connections_me_current 1384
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 196472
telemt_upstream_connect_attempt_total 47890
telemt_upstream_connect_success_total 47559
telemt_upstream_connect_fail_total 136
telemt_upstream_connect_attempts_per_request{bucket="1"} 47695
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24662
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21445
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 396
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1056
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 136
telemt_me_keepalive_timeout_total 58
telemt_me_reconnect_attempts_total 1902
telemt_me_reconnect_success_total 861
telemt_me_reader_eof_total 801
telemt_me_idle_close_by_peer_total 801
telemt_me_route_drop_no_conn_total 2119375
telemt_me_route_drop_channel_closed_total 113
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4567432
telemt_me_endpoint_quarantine_total 704
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 766
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
telemt_me_writers_active_current 46
telemt_desync_total 22114
telemt_desync_full_logged_total 7397
telemt_desync_suppressed_total 14717
telemt_desync_frames_bucket_total{bucket="1_2"} 5401
telemt_desync_frames_bucket_total{bucket="3_10"} 8473
telemt_desync_frames_bucket_total{bucket="gt_10"} 8240
telemt_pool_swap_total 110
telemt_pool_force_close_total 3221
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 374
telemt_me_draining_writers_reap_progress_total 34181
telemt_me_writer_removed_unexpected_total 776
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2845
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 32123
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3006
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 215
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 30960
telemt_me_writer_teardown_success_total{mode="normal"} 34968
telemt_me_writer_teardown_noop_total 34192
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 66654
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 68013
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 68452
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 68910
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 69117
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 69142
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 69160
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 69160
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 69160
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 69160
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 69160
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 69160
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 69160
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 25.689316
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 69160
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 374
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 746
telemt_me_writer_restored_fallback_total 5
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 25
telemt_user_connections_total{user="hello"} 4568172
telemt_user_connections_current{user="hello"} 1384
telemt_user_octets_from_client{user="hello"} 132555993903 (123.45 GB)
telemt_user_octets_to_client{user="hello"} 2086609878103 (1.90 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 674
telemt_user_unique_ips_recent_window{user="hello"} 132
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 102493.0 (28h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20156922
telemt_connections_bad_total 1534236
telemt_connections_current 2104
telemt_connections_me_current 2104
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 588810
telemt_upstream_connect_attempt_total 190774
telemt_upstream_connect_success_total 173081
telemt_upstream_connect_fail_total 16050
telemt_upstream_connect_attempts_per_request{bucket="1"} 189131
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 122058
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 40912
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1221
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8890
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16050
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 64468
telemt_me_reconnect_success_total 2206
telemt_me_reader_eof_total 1387
telemt_me_idle_close_by_peer_total 1386
telemt_me_route_drop_no_conn_total 39474781
telemt_me_route_drop_channel_closed_total 124
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16360903
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 789
telemt_me_single_endpoint_outage_enter_total 125
telemt_me_single_endpoint_outage_exit_total 125
telemt_me_single_endpoint_outage_reconnect_attempt_total 261
telemt_me_single_endpoint_outage_reconnect_success_total 64
telemt_me_single_endpoint_quarantine_bypass_total 261
telemt_me_single_endpoint_shadow_rotate_total 798
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 58
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
telemt_desync_total 31657
telemt_desync_full_logged_total 9453
telemt_desync_suppressed_total 22204
telemt_desync_frames_bucket_total{bucket="1_2"} 6874
telemt_desync_frames_bucket_total{bucket="3_10"} 14049
telemt_desync_frames_bucket_total{bucket="gt_10"} 10734
telemt_pool_swap_total 105
telemt_pool_force_close_total 3464
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 772
telemt_me_draining_writers_reap_progress_total 31915
telemt_me_writer_removed_unexpected_total 2046
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4317
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 29380
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2942
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 522
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 28451
telemt_me_writer_teardown_success_total{mode="normal"} 33697
telemt_me_writer_teardown_noop_total 31941
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 59014
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 61389
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 62655
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 64274
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 65202
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 65537
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 65619
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 65621
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 65624
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 65629
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 65629
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 65633
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 65638
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 212.860132
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 65638
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 772
telemt_me_refill_failed_total 3792
telemt_me_writer_restored_same_endpoint_total 1530
telemt_me_writer_restored_fallback_total 21
telemt_me_no_writer_failfast_total 666
telemt_me_async_recovery_trigger_total 14678
telemt_me_writer_removed_unexpected_minus_restored_total 495
telemt_user_connections_total{user="hello"} 16488498
telemt_user_connections_current{user="hello"} 2104
telemt_user_octets_from_client{user="hello"} 199298391652 (185.61 GB)
telemt_user_octets_to_client{user="hello"} 1154911915834 (1.05 TB)
telemt_user_msgs_from_client{user="hello"} 367794
telemt_user_msgs_to_client{user="hello"} 650852
telemt_user_unique_ips_current{user="hello"} 994
telemt_user_unique_ips_recent_window{user="hello"} 231
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 102460.3 (28h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5904415
telemt_connections_bad_total 555594
telemt_connections_current 1436
telemt_connections_me_current 1436
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 122773
telemt_upstream_connect_attempt_total 56142
telemt_upstream_connect_success_total 55486
telemt_upstream_connect_fail_total 563
telemt_upstream_connect_attempts_per_request{bucket="1"} 56049
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32768
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22374
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 343
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 563
telemt_me_reconnect_attempts_total 69426
telemt_me_reconnect_success_total 1736
telemt_me_reader_eof_total 1508
telemt_me_idle_close_by_peer_total 1507
telemt_me_route_drop_no_conn_total 2370494
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4605077
telemt_me_endpoint_quarantine_total 689
telemt_me_single_endpoint_outage_enter_total 23
telemt_me_single_endpoint_outage_exit_total 23
telemt_me_single_endpoint_outage_reconnect_attempt_total 24
telemt_me_single_endpoint_outage_reconnect_success_total 23
telemt_me_single_endpoint_quarantine_bypass_total 24
telemt_me_single_endpoint_shadow_rotate_total 770
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
telemt_me_writers_active_current 43
telemt_desync_total 23151
telemt_desync_full_logged_total 8121
telemt_desync_suppressed_total 15030
telemt_desync_frames_bucket_total{bucket="1_2"} 4394
telemt_desync_frames_bucket_total{bucket="3_10"} 8962
telemt_desync_frames_bucket_total{bucket="gt_10"} 9795
telemt_pool_swap_total 105
telemt_pool_force_close_total 3066
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 384
telemt_me_draining_writers_reap_progress_total 35628
telemt_me_writer_removed_unexpected_total 1552
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3744
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 33461
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2665
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 401
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 32562
telemt_me_writer_teardown_success_total{mode="normal"} 37205
telemt_me_writer_teardown_noop_total 35629
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 71589
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 72406
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 72682
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 72802
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 72831
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 72834
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 72834
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 72834
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 72834
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 72834
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 72834
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 72834
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 72834
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.047061
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 72834
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 384
telemt_me_refill_failed_total 4196
telemt_me_writer_restored_same_endpoint_total 1458
telemt_me_writer_restored_fallback_total 32
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7305
telemt_me_writer_removed_unexpected_minus_restored_total 62
telemt_user_connections_total{user="hello"} 4598092
telemt_user_connections_current{user="hello"} 1436
telemt_user_octets_from_client{user="hello"} 122953242552 (114.51 GB)
telemt_user_octets_to_client{user="hello"} 1881142841010 (1.71 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 730
telemt_user_unique_ips_recent_window{user="hello"} 146
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 39296.2 (10h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3793760
telemt_connections_bad_total 138213
telemt_connections_current 1140
telemt_connections_me_current 1140
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 1565986
telemt_upstream_connect_attempt_total 24454
telemt_upstream_connect_success_total 24295
telemt_upstream_connect_fail_total 152
telemt_upstream_connect_attempts_per_request{bucket="1"} 24447
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15854
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8373
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 68
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 152
telemt_me_reconnect_attempts_total 45724
telemt_me_reconnect_success_total 920
telemt_me_reader_eof_total 595
telemt_me_idle_close_by_peer_total 595
telemt_me_route_drop_no_conn_total 1006797
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1842880
telemt_me_endpoint_quarantine_total 290
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 50
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 50
telemt_me_single_endpoint_shadow_rotate_total 298
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 8
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
telemt_desync_total 10135
telemt_desync_full_logged_total 3489
telemt_desync_suppressed_total 6646
telemt_desync_frames_bucket_total{bucket="1_2"} 1803
telemt_desync_frames_bucket_total{bucket="3_10"} 3874
telemt_desync_frames_bucket_total{bucket="gt_10"} 4458
telemt_pool_swap_total 42
telemt_pool_force_close_total 1347
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 127
telemt_me_draining_writers_reap_progress_total 13757
telemt_me_writer_removed_unexpected_total 674
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1384
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13068
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1141
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 206
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 12410
telemt_me_writer_teardown_success_total{mode="normal"} 14452
telemt_me_writer_teardown_noop_total 13759
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 27717
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 27991
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 28105
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 28211
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 28211
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 28211
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 28211
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 28211
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 28211
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 28211
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 28211
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 28211
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 28211
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.299216
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 28211
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 127
telemt_me_refill_failed_total 2603
telemt_me_writer_restored_same_endpoint_total 823
telemt_me_writer_restored_fallback_total 12
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4264
telemt_user_connections_total{user="hello"} 1846596
telemt_user_connections_current{user="hello"} 1140
telemt_user_octets_from_client{user="hello"} 53269181088 (49.61 GB)
telemt_user_octets_to_client{user="hello"} 791884566182 (737.50 GB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 619
telemt_user_unique_ips_recent_window{user="hello"} 118
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 20266.9 (5h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 173855
telemt_connections_bad_total 1491
telemt_connections_current 249
telemt_connections_me_current 249
telemt_handshake_timeouts_total 4788
telemt_upstream_connect_attempt_total 9568
telemt_upstream_connect_success_total 9544
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 9566
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4075
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5398
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 71
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_reconnect_attempts_total 213
telemt_me_reconnect_success_total 129
telemt_me_reader_eof_total 130
telemt_me_idle_close_by_peer_total 130
telemt_me_route_drop_no_conn_total 48381
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 152928
telemt_me_endpoint_quarantine_total 202
telemt_me_single_endpoint_shadow_rotate_total 180
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 35
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_desync_total 996
telemt_desync_full_logged_total 249
telemt_desync_suppressed_total 747
telemt_desync_frames_bucket_total{bucket="1_2"} 388
telemt_desync_frames_bucket_total{bucket="3_10"} 364
telemt_desync_frames_bucket_total{bucket="gt_10"} 244
telemt_pool_swap_total 22
telemt_pool_force_close_total 495
telemt_me_writer_close_signal_drop_total 20
telemt_me_draining_writers_reap_progress_total 8607
telemt_me_writer_removed_unexpected_total 127
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 576
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 8161
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 493
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 8112
telemt_me_writer_teardown_success_total{mode="normal"} 8737
telemt_me_writer_teardown_noop_total 8607
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 17181
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 17316
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 17334
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 17344
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 17344
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 17344
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 17344
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 17344
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 17344
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 17344
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 17344
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 17344
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 17344
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.866460
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 17344
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 20
telemt_me_refill_failed_total 5
telemt_me_writer_restored_same_endpoint_total 118
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 152638
telemt_user_connections_current{user="hello"} 249
telemt_user_octets_from_client{user="hello"} 2847914964 (2.65 GB)
telemt_user_octets_to_client{user="hello"} 90687033468 (84.46 GB)
telemt_user_unique_ips_current{user="hello"} 136
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 102464.7 (28h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7140636
telemt_connections_bad_total 726146
telemt_connections_current 1760
telemt_connections_me_current 1760
telemt_handshake_timeouts_total 203774
telemt_upstream_connect_attempt_total 39610
telemt_upstream_connect_success_total 39458
telemt_upstream_connect_fail_total 115
telemt_upstream_connect_attempts_per_request{bucket="1"} 39573
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19566
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19851
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 115
telemt_me_reconnect_attempts_total 1529
telemt_me_reconnect_success_total 814
telemt_me_reader_eof_total 796
telemt_me_idle_close_by_peer_total 796
telemt_me_route_drop_no_conn_total 2108570
telemt_me_route_drop_channel_closed_total 52
telemt_me_route_drop_queue_full_total 23
telemt_me_route_drop_queue_full_profile_total{profile="high"} 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5378494
telemt_me_endpoint_quarantine_total 708
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 787
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
telemt_desync_total 20783
telemt_desync_full_logged_total 6950
telemt_desync_suppressed_total 13833
telemt_desync_frames_bucket_total{bucket="1_2"} 5051
telemt_desync_frames_bucket_total{bucket="3_10"} 7531
telemt_desync_frames_bucket_total{bucket="gt_10"} 8201
telemt_pool_swap_total 113
telemt_pool_force_close_total 3064
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 376
telemt_me_draining_writers_reap_progress_total 35674
telemt_me_writer_removed_unexpected_total 767
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2860
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 33600
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2976
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 32610
telemt_me_writer_teardown_success_total{mode="normal"} 36460
telemt_me_writer_teardown_noop_total 35676
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 70787
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 71670
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 71848
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 72048
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 72136
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 72136
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 72136
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 72136
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 72136
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 72136
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 72136
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 72136
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 72136
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.591245
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 72136
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 376
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 724
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 5353603
telemt_user_connections_current{user="hello"} 1760
telemt_user_octets_from_client{user="hello"} 108292042656 (100.85 GB)
telemt_user_octets_to_client{user="hello"} 2507692878364 (2.28 TB)
telemt_user_unique_ips_current{user="hello"} 784
telemt_user_unique_ips_recent_window{user="hello"} 140
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 102461.4 (28h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6154201
telemt_connections_bad_total 606948
telemt_connections_current 1452
telemt_connections_me_current 1452
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 169324
telemt_upstream_connect_attempt_total 55451
telemt_upstream_connect_success_total 55035
telemt_upstream_connect_fail_total 357
telemt_upstream_connect_attempts_per_request{bucket="1"} 55392
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32358
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21544
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 615
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 357
telemt_me_reconnect_attempts_total 5435
telemt_me_reconnect_success_total 1124
telemt_me_reader_eof_total 1006
telemt_me_idle_close_by_peer_total 1006
telemt_me_seq_mismatch_total 44
telemt_me_route_drop_no_conn_total 2162596
telemt_me_route_drop_channel_closed_total 189
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4747600
telemt_me_endpoint_quarantine_total 816
telemt_me_single_endpoint_outage_enter_total 27
telemt_me_single_endpoint_outage_exit_total 27
telemt_me_single_endpoint_outage_reconnect_attempt_total 27
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 27
telemt_me_single_endpoint_shadow_rotate_total 782
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
telemt_desync_total 19562
telemt_desync_full_logged_total 6579
telemt_desync_suppressed_total 12983
telemt_desync_frames_bucket_total{bucket="1_2"} 4897
telemt_desync_frames_bucket_total{bucket="3_10"} 7114
telemt_desync_frames_bucket_total{bucket="gt_10"} 7551
telemt_pool_swap_total 111
telemt_pool_force_close_total 3023
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 372
telemt_me_draining_writers_reap_progress_total 34283
telemt_me_writer_removed_unexpected_total 1018
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3351
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 31997
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2800
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 223
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 31260
telemt_me_writer_teardown_success_total{mode="normal"} 35348
telemt_me_writer_teardown_noop_total 34287
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 68010
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 69057
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 69402
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 69597
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 69635
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 69635
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 69635
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 69635
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 69635
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 69635
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 69635
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 69635
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 69635
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.972133
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 69635
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 372
telemt_me_refill_failed_total 249
telemt_me_writer_restored_same_endpoint_total 876
telemt_me_writer_restored_fallback_total 57
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 76
telemt_me_writer_removed_unexpected_minus_restored_total 85
telemt_user_connections_total{user="hello"} 4750771
telemt_user_connections_current{user="hello"} 1452
telemt_user_octets_from_client{user="hello"} 89595832225 (83.44 GB)
telemt_user_octets_to_client{user="hello"} 2035897761956 (1.85 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 672
telemt_user_unique_ips_recent_window{user="hello"} 155
```