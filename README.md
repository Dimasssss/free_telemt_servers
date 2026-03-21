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

# Server Metrics 2026-03-21 20:08:13 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 84740.4 (23h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3040750
telemt_connections_bad_total 177337
telemt_connections_current 1038
telemt_connections_me_current 1038
telemt_relay_adaptive_promotions_total 3
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 93273
telemt_upstream_connect_attempt_total 34681
telemt_upstream_connect_success_total 34537
telemt_upstream_connect_fail_total 101
telemt_upstream_connect_attempts_per_request{bucket="1"} 34638
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13932
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20483
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 54
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 68
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 101
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 107
telemt_me_reconnect_attempts_total 1880
telemt_me_reconnect_success_total 753
telemt_me_reader_eof_total 722
telemt_me_idle_close_by_peer_total 722
telemt_me_route_drop_no_conn_total 2613387
telemt_me_route_drop_channel_closed_total 840
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2459584
telemt_me_writer_pick_total{mode="p2c",result="full"} 26
telemt_me_endpoint_quarantine_total 575
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 659
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 26
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
telemt_desync_total 9808
telemt_desync_full_logged_total 3425
telemt_desync_suppressed_total 6383
telemt_desync_frames_bucket_total{bucket="1_2"} 2139
telemt_desync_frames_bucket_total{bucket="3_10"} 3706
telemt_desync_frames_bucket_total{bucket="gt_10"} 3963
telemt_pool_swap_total 92
telemt_pool_force_close_total 2761
telemt_pool_stale_pick_total 31
telemt_me_writer_close_signal_drop_total 638
telemt_me_draining_writers_reap_progress_total 28368
telemt_me_writer_removed_unexpected_total 704
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2390
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26422
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2622
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 139
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 25607
telemt_me_writer_teardown_success_total{mode="normal"} 28812
telemt_me_writer_teardown_noop_total 28376
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 46760
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 48640
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 50259
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 53187
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 55609
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 56811
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 57158
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 57183
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 57187
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 57188
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 57188
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 57188
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 57188
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 297.274881
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 57188
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 638
telemt_me_refill_failed_total 62
telemt_me_writer_restored_same_endpoint_total 647
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 49
telemt_user_connections_total{user="hello"} 2459273
telemt_user_connections_current{user="hello"} 1038
telemt_user_octets_from_client{user="hello"} 36409584557 (33.91 GB)
telemt_user_octets_to_client{user="hello"} 621464821914 (578.78 GB)
telemt_user_msgs_from_client{user="hello"} 7227
telemt_user_msgs_to_client{user="hello"} 6949
telemt_user_unique_ips_current{user="hello"} 425
telemt_user_unique_ips_recent_window{user="hello"} 141
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 9878.3 (2h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 406075
telemt_connections_bad_total 18508
telemt_connections_current 1354
telemt_connections_me_current 1354
telemt_handshake_timeouts_total 14206
telemt_upstream_connect_attempt_total 3919
telemt_upstream_connect_success_total 3836
telemt_upstream_connect_fail_total 72
telemt_upstream_connect_attempts_per_request{bucket="1"} 3908
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1671
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2150
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 72
telemt_me_reconnect_attempts_total 178
telemt_me_reconnect_success_total 131
telemt_me_reader_eof_total 107
telemt_me_idle_close_by_peer_total 107
telemt_me_route_drop_no_conn_total 255638
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 334214
telemt_me_endpoint_quarantine_total 77
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 77
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
telemt_me_writers_active_current 44
telemt_desync_total 1447
telemt_desync_full_logged_total 813
telemt_desync_suppressed_total 634
telemt_desync_frames_bucket_total{bucket="1_2"} 292
telemt_desync_frames_bucket_total{bucket="3_10"} 544
telemt_desync_frames_bucket_total{bucket="gt_10"} 611
telemt_pool_swap_total 10
telemt_pool_force_close_total 309
telemt_me_writer_close_signal_drop_total 30
telemt_me_draining_writers_reap_progress_total 3377
telemt_me_writer_removed_unexpected_total 101
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 295
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 3176
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 302
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 3068
telemt_me_writer_teardown_success_total{mode="normal"} 3471
telemt_me_writer_teardown_noop_total 3377
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 6621
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 6772
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 6801
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 6848
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 6848
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 6848
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 6848
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 6848
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 6848
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 6848
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 6848
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 6848
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 6848
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.410891
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 6848
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 30
telemt_me_refill_failed_total 2
telemt_me_writer_restored_same_endpoint_total 91
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 333842
telemt_user_connections_current{user="hello"} 1354
telemt_user_octets_from_client{user="hello"} 5343370428 (4.98 GB)
telemt_user_octets_to_client{user="hello"} 95179977456 (88.64 GB)
telemt_user_unique_ips_current{user="hello"} 839
telemt_user_unique_ips_recent_window{user="hello"} 353
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 84738.2 (23h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6736592
telemt_connections_bad_total 517325
telemt_connections_current 3550
telemt_connections_me_current 3550
telemt_handshake_timeouts_total 211564
telemt_upstream_connect_attempt_total 30494
telemt_upstream_connect_success_total 30432
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 30438
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13700
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16602
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 124
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1280
telemt_me_reconnect_success_total 657
telemt_me_reader_eof_total 666
telemt_me_idle_close_by_peer_total 666
telemt_me_route_drop_no_conn_total 4308802
telemt_me_route_drop_channel_closed_total 62
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5529905
telemt_me_endpoint_quarantine_total 527
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 628
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 20
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
telemt_desync_total 22665
telemt_desync_full_logged_total 7540
telemt_desync_suppressed_total 15125
telemt_desync_frames_bucket_total{bucket="1_2"} 4746
telemt_desync_frames_bucket_total{bucket="3_10"} 9022
telemt_desync_frames_bucket_total{bucket="gt_10"} 8897
telemt_pool_swap_total 91
telemt_pool_force_close_total 3016
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 494
telemt_me_draining_writers_reap_progress_total 27732
telemt_me_writer_removed_unexpected_total 641
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2391
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 25632
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 37
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2786
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 230
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 24716
telemt_me_writer_teardown_success_total{mode="normal"} 28023
telemt_me_writer_teardown_noop_total 27769
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 50693
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 52283
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 53106
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 54284
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 55067
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 55532
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 55781
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 55792
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 55792
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 55792
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 55792
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 55792
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 55792
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 131.040573
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 55792
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 494
telemt_me_refill_failed_total 32
telemt_me_writer_restored_same_endpoint_total 592
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 44
telemt_user_connections_total{user="hello"} 5523273
telemt_user_connections_current{user="hello"} 3550
telemt_user_octets_from_client{user="hello"} 92230023660 (85.90 GB)
telemt_user_octets_to_client{user="hello"} 1724498830920 (1.57 TB)
telemt_user_unique_ips_current{user="hello"} 1543
telemt_user_unique_ips_recent_window{user="hello"} 448
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 84739.5 (23h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5437670
telemt_connections_bad_total 518392
telemt_connections_current 3565
telemt_connections_me_current 3565
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 180458
telemt_upstream_connect_attempt_total 34654
telemt_upstream_connect_success_total 34338
telemt_upstream_connect_fail_total 162
telemt_upstream_connect_attempts_per_request{bucket="1"} 34500
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17394
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16376
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 541
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 162
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 1646
telemt_me_reconnect_success_total 689
telemt_me_reader_eof_total 661
telemt_me_idle_close_by_peer_total 661
telemt_me_route_drop_no_conn_total 1881623
telemt_me_route_drop_channel_closed_total 215
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4073590
telemt_me_endpoint_quarantine_total 521
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 646
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
telemt_desync_total 19265
telemt_desync_full_logged_total 6384
telemt_desync_suppressed_total 12881
telemt_desync_frames_bucket_total{bucket="1_2"} 4691
telemt_desync_frames_bucket_total{bucket="3_10"} 7458
telemt_desync_frames_bucket_total{bucket="gt_10"} 7116
telemt_pool_swap_total 93
telemt_pool_force_close_total 2790
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 315
telemt_me_draining_writers_reap_progress_total 26566
telemt_me_writer_removed_unexpected_total 641
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2314
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 24821
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2598
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 192
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 23776
telemt_me_writer_teardown_success_total{mode="normal"} 27135
telemt_me_writer_teardown_noop_total 26571
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 50846
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 52199
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 52676
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 53192
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 53537
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 53693
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 53706
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 53706
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 53706
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 53706
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 53706
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 53706
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 53706
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 40.615281
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 53706
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 315
telemt_me_refill_failed_total 51
telemt_me_writer_restored_same_endpoint_total 589
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 44
telemt_user_connections_total{user="hello"} 4070627
telemt_user_connections_current{user="hello"} 3565
telemt_user_octets_from_client{user="hello"} 122597368637 (114.18 GB)
telemt_user_octets_to_client{user="hello"} 1849671231743 (1.68 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1344
telemt_user_unique_ips_recent_window{user="hello"} 428
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 84703.4 (23h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5369313
telemt_connections_bad_total 485397
telemt_connections_current 3387
telemt_connections_me_current 3387
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 162252
telemt_upstream_connect_attempt_total 41030
telemt_upstream_connect_success_total 40766
telemt_upstream_connect_fail_total 134
telemt_upstream_connect_attempts_per_request{bucket="1"} 40900
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21594
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17809
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 327
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1036
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 134
telemt_me_keepalive_timeout_total 58
telemt_me_reconnect_attempts_total 1705
telemt_me_reconnect_success_total 741
telemt_me_reader_eof_total 685
telemt_me_idle_close_by_peer_total 685
telemt_me_route_drop_no_conn_total 1943456
telemt_me_route_drop_channel_closed_total 93
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4057259
telemt_me_endpoint_quarantine_total 574
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 630
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
telemt_desync_total 18895
telemt_desync_full_logged_total 6160
telemt_desync_suppressed_total 12735
telemt_desync_frames_bucket_total{bucket="1_2"} 4680
telemt_desync_frames_bucket_total{bucket="3_10"} 7160
telemt_desync_frames_bucket_total{bucket="gt_10"} 7055
telemt_pool_swap_total 91
telemt_pool_force_close_total 2653
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 328
telemt_me_draining_writers_reap_progress_total 27981
telemt_me_writer_removed_unexpected_total 654
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2381
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26275
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2443
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 210
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 25328
telemt_me_writer_teardown_success_total{mode="normal"} 28656
telemt_me_writer_teardown_noop_total 27991
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 54512
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 55668
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 56037
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 56450
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 56624
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 56644
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 56647
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 56647
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 56647
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 56647
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 56647
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 56647
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 56647
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 20.690238
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 56647
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 328
telemt_me_refill_failed_total 53
telemt_me_writer_restored_same_endpoint_total 637
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 13
telemt_user_connections_total{user="hello"} 4059748
telemt_user_connections_current{user="hello"} 3387
telemt_user_octets_from_client{user="hello"} 118845718795 (110.68 GB)
telemt_user_octets_to_client{user="hello"} 1850263882171 (1.68 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 1388
telemt_user_unique_ips_recent_window{user="hello"} 412
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 84743.0 (23h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18683236
telemt_connections_bad_total 1188499
telemt_connections_current 4547
telemt_connections_me_current 4547
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 522769
telemt_upstream_connect_attempt_total 174102
telemt_upstream_connect_success_total 157236
telemt_upstream_connect_fail_total 15496
telemt_upstream_connect_attempts_per_request{bucket="1"} 172732
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 112097
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35295
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1024
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8820
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15496
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 4639
telemt_me_reconnect_success_total 1727
telemt_me_reader_eof_total 1184
telemt_me_idle_close_by_peer_total 1183
telemt_me_route_drop_no_conn_total 38247435
telemt_me_route_drop_channel_closed_total 110
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 15385794
telemt_me_endpoint_quarantine_total 620
telemt_me_single_endpoint_outage_enter_total 98
telemt_me_single_endpoint_outage_exit_total 98
telemt_me_single_endpoint_outage_reconnect_attempt_total 216
telemt_me_single_endpoint_outage_reconnect_success_total 47
telemt_me_single_endpoint_quarantine_bypass_total 216
telemt_me_single_endpoint_shadow_rotate_total 655
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
telemt_me_writers_active_current 41
telemt_desync_total 28523
telemt_desync_full_logged_total 8427
telemt_desync_suppressed_total 20096
telemt_desync_frames_bucket_total{bucket="1_2"} 6134
telemt_desync_frames_bucket_total{bucket="3_10"} 12714
telemt_desync_frames_bucket_total{bucket="gt_10"} 9675
telemt_pool_swap_total 87
telemt_pool_force_close_total 2862
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 647
telemt_me_draining_writers_reap_progress_total 26113
telemt_me_writer_removed_unexpected_total 1636
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3483
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 24024
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 15
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2414
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 448
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 23251
telemt_me_writer_teardown_success_total{mode="normal"} 27507
telemt_me_writer_teardown_noop_total 26129
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 47910
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 49961
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 51088
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 52438
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 53237
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 53548
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 53617
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 53619
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 53622
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 53627
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 53627
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 53631
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 53636
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 198.828503
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 53636
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 647
telemt_me_refill_failed_total 100
telemt_me_writer_restored_same_endpoint_total 1196
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 160
telemt_me_writer_removed_unexpected_minus_restored_total 429
telemt_user_connections_total{user="hello"} 15504752
telemt_user_connections_current{user="hello"} 4547
telemt_user_octets_from_client{user="hello"} 142111741439 (132.35 GB)
telemt_user_octets_to_client{user="hello"} 949612050295 (884.40 GB)
telemt_user_msgs_from_client{user="hello"} 352315
telemt_user_msgs_to_client{user="hello"} 633668
telemt_user_unique_ips_current{user="hello"} 1698
telemt_user_unique_ips_recent_window{user="hello"} 749
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 84710.0 (23h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5295290
telemt_connections_bad_total 512577
telemt_connections_current 3321
telemt_connections_me_current 3321
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 108966
telemt_upstream_connect_attempt_total 44083
telemt_upstream_connect_success_total 43619
telemt_upstream_connect_fail_total 382
telemt_upstream_connect_attempts_per_request{bucket="1"} 44001
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25253
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18041
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 324
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 382
telemt_me_reconnect_attempts_total 3459
telemt_me_reconnect_success_total 1209
telemt_me_reader_eof_total 1183
telemt_me_idle_close_by_peer_total 1183
telemt_me_route_drop_no_conn_total 2227708
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 36
telemt_me_route_drop_queue_full_profile_total{profile="high"} 36
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4105040
telemt_me_endpoint_quarantine_total 506
telemt_me_single_endpoint_outage_enter_total 13
telemt_me_single_endpoint_outage_exit_total 13
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 13
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 626
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
telemt_me_writers_active_current 46
telemt_me_writers_warm_current 38
telemt_desync_total 20269
telemt_desync_full_logged_total 7041
telemt_desync_suppressed_total 13228
telemt_desync_frames_bucket_total{bucket="1_2"} 3892
telemt_desync_frames_bucket_total{bucket="3_10"} 7935
telemt_desync_frames_bucket_total{bucket="gt_10"} 8442
telemt_pool_swap_total 85
telemt_pool_force_close_total 2499
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 310
telemt_me_draining_writers_reap_progress_total 28735
telemt_me_writer_removed_unexpected_total 1146
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2910
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26983
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2155
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 344
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26236
telemt_me_writer_teardown_success_total{mode="normal"} 29893
telemt_me_writer_teardown_noop_total 28736
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 57619
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 58280
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 58506
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 58597
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 58626
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 58629
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 58629
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 58629
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 58629
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 58629
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 58629
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 58629
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 58629
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 6.739860
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 58629
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 310
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 1027
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 104
telemt_user_connections_total{user="hello"} 4095502
telemt_user_connections_current{user="hello"} 3321
telemt_user_octets_from_client{user="hello"} 109044816713 (101.56 GB)
telemt_user_octets_to_client{user="hello"} 1654286032267 (1.50 TB)
telemt_user_msgs_from_client{user="hello"} 59697
telemt_user_msgs_to_client{user="hello"} 266554
telemt_user_unique_ips_current{user="hello"} 1445
telemt_user_unique_ips_recent_window{user="hello"} 392
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 21545.9 (5h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2925021
telemt_connections_bad_total 109803
telemt_connections_current 3014
telemt_connections_me_current 3014
telemt_handshake_timeouts_total 1258241
telemt_upstream_connect_attempt_total 6889
telemt_upstream_connect_success_total 6792
telemt_upstream_connect_fail_total 91
telemt_upstream_connect_attempts_per_request{bucket="1"} 6883
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2990
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3755
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 47
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 91
telemt_me_reconnect_attempts_total 671
telemt_me_reconnect_success_total 203
telemt_me_reader_eof_total 188
telemt_me_idle_close_by_peer_total 188
telemt_me_route_drop_no_conn_total 872560
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1383816
telemt_me_endpoint_quarantine_total 102
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 157
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 2
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
telemt_desync_total 7596
telemt_desync_full_logged_total 2493
telemt_desync_suppressed_total 5103
telemt_desync_frames_bucket_total{bucket="1_2"} 1346
telemt_desync_frames_bucket_total{bucket="3_10"} 2850
telemt_desync_frames_bucket_total{bucket="gt_10"} 3400
telemt_pool_swap_total 22
telemt_pool_force_close_total 710
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 69
telemt_me_draining_writers_reap_progress_total 5990
telemt_me_writer_removed_unexpected_total 185
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 562
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 5618
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 622
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 5280
telemt_me_writer_teardown_success_total{mode="normal"} 6180
telemt_me_writer_teardown_noop_total 5990
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 11922
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 12051
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 12094
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 12170
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 12170
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 12170
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 12170
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 12170
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 12170
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 12170
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 12170
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 12170
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 12170
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.954725
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 12170
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 69
telemt_me_refill_failed_total 27
telemt_me_writer_restored_same_endpoint_total 168
telemt_me_async_recovery_trigger_total 6
telemt_me_writer_removed_unexpected_minus_restored_total 17
telemt_user_connections_total{user="hello"} 1380196
telemt_user_connections_current{user="hello"} 3014
telemt_user_octets_from_client{user="hello"} 42485924092 (39.57 GB)
telemt_user_octets_to_client{user="hello"} 561817695472 (523.23 GB)
telemt_user_unique_ips_current{user="hello"} 1244
telemt_user_unique_ips_recent_window{user="hello"} 397
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 2516.9 (0h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 26067
telemt_connections_bad_total 75
telemt_connections_current 736
telemt_connections_me_current 736
telemt_handshake_timeouts_total 633
telemt_upstream_connect_attempt_total 1068
telemt_upstream_connect_success_total 1066
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 1068
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 426
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 620
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 41
telemt_me_reconnect_success_total 11
telemt_me_reader_eof_total 11
telemt_me_idle_close_by_peer_total 11
telemt_me_route_drop_no_conn_total 7361
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 24065
telemt_me_endpoint_quarantine_total 11
telemt_me_single_endpoint_shadow_rotate_total 23
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
telemt_desync_total 128
telemt_desync_full_logged_total 33
telemt_desync_suppressed_total 95
telemt_desync_frames_bucket_total{bucket="1_2"} 58
telemt_desync_frames_bucket_total{bucket="3_10"} 40
telemt_desync_frames_bucket_total{bucket="gt_10"} 30
telemt_pool_swap_total 2
telemt_pool_force_close_total 58
telemt_me_writer_close_signal_drop_total 1
telemt_me_draining_writers_reap_progress_total 903
telemt_me_writer_removed_unexpected_total 11
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 57
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 857
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 58
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 845
telemt_me_writer_teardown_success_total{mode="normal"} 914
telemt_me_writer_teardown_noop_total 903
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 1812
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 1817
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 1817
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 1817
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 1817
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 1817
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 1817
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 1817
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 1817
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 1817
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 1817
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 1817
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 1817
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.050076
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 1817
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1
telemt_me_refill_failed_total 2
telemt_me_writer_restored_same_endpoint_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 24038
telemt_user_connections_current{user="hello"} 736
telemt_user_octets_from_client{user="hello"} 818458668 (780.54 MB)
telemt_user_octets_to_client{user="hello"} 19635821432 (18.29 GB)
telemt_user_unique_ips_current{user="hello"} 278
telemt_user_unique_ips_recent_window{user="hello"} 99
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 84714.6 (23h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6266331
telemt_connections_bad_total 641944
telemt_connections_current 3443
telemt_connections_me_current 3443
telemt_handshake_timeouts_total 182944
telemt_upstream_connect_attempt_total 32277
telemt_upstream_connect_success_total 32147
telemt_upstream_connect_fail_total 93
telemt_upstream_connect_attempts_per_request{bucket="1"} 32240
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15898
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16210
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 93
telemt_me_reconnect_attempts_total 1358
telemt_me_reconnect_success_total 696
telemt_me_reader_eof_total 669
telemt_me_idle_close_by_peer_total 669
telemt_me_route_drop_no_conn_total 1944473
telemt_me_route_drop_channel_closed_total 51
telemt_me_route_drop_queue_full_total 21
telemt_me_route_drop_queue_full_profile_total{profile="high"} 21
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4811733
telemt_me_endpoint_quarantine_total 567
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 644
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
telemt_me_writers_active_current 44
telemt_desync_total 18174
telemt_desync_full_logged_total 6018
telemt_desync_suppressed_total 12156
telemt_desync_frames_bucket_total{bucket="1_2"} 4444
telemt_desync_frames_bucket_total{bucket="3_10"} 6647
telemt_desync_frames_bucket_total{bucket="gt_10"} 7083
telemt_pool_swap_total 94
telemt_pool_force_close_total 2531
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 318
telemt_me_draining_writers_reap_progress_total 28943
telemt_me_writer_removed_unexpected_total 653
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2349
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27253
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2456
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 75
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26412
telemt_me_writer_teardown_success_total{mode="normal"} 29602
telemt_me_writer_teardown_noop_total 28945
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 57384
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 58137
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 58280
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 58459
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 58547
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 58547
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 58547
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 58547
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 58547
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 58547
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 58547
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 58547
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 58547
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 9.467620
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 58547
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 318
telemt_me_refill_failed_total 34
telemt_me_writer_restored_same_endpoint_total 622
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 26
telemt_user_connections_total{user="hello"} 4787896
telemt_user_connections_current{user="hello"} 3443
telemt_user_octets_from_client{user="hello"} 95516718736 (88.96 GB)
telemt_user_octets_to_client{user="hello"} 2219922430292 (2.02 TB)
telemt_user_unique_ips_current{user="hello"} 1227
telemt_user_unique_ips_recent_window{user="hello"} 883
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 84711.4 (23h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5291576
telemt_connections_bad_total 491581
telemt_connections_current 4171
telemt_connections_me_current 4171
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 153132
telemt_upstream_connect_attempt_total 48639
telemt_upstream_connect_success_total 48280
telemt_upstream_connect_fail_total 300
telemt_upstream_connect_attempts_per_request{bucket="1"} 48580
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29111
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18038
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 613
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 300
telemt_me_reconnect_attempts_total 4435
telemt_me_reconnect_success_total 978
telemt_me_reader_eof_total 866
telemt_me_idle_close_by_peer_total 866
telemt_me_seq_mismatch_total 36
telemt_me_route_drop_no_conn_total 1997760
telemt_me_route_drop_channel_closed_total 184
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4188135
telemt_me_endpoint_quarantine_total 677
telemt_me_single_endpoint_outage_enter_total 25
telemt_me_single_endpoint_outage_exit_total 25
telemt_me_single_endpoint_outage_reconnect_attempt_total 25
telemt_me_single_endpoint_outage_reconnect_success_total 24
telemt_me_single_endpoint_quarantine_bypass_total 25
telemt_me_single_endpoint_shadow_rotate_total 642
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
telemt_me_writers_active_current 43
telemt_desync_total 16793
telemt_desync_full_logged_total 5694
telemt_desync_suppressed_total 11099
telemt_desync_frames_bucket_total{bucket="1_2"} 4145
telemt_desync_frames_bucket_total{bucket="3_10"} 6189
telemt_desync_frames_bucket_total{bucket="gt_10"} 6459
telemt_pool_swap_total 92
telemt_pool_force_close_total 2462
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 312
telemt_me_draining_writers_reap_progress_total 28153
telemt_me_writer_removed_unexpected_total 877
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2816
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26253
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2270
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 192
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 25691
telemt_me_writer_teardown_success_total{mode="normal"} 29069
telemt_me_writer_teardown_noop_total 28155
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 55869
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 56749
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 57013
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 57192
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 57224
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 57224
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 57224
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 57224
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 57224
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 57224
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 57224
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 57224
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 57224
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 9.274079
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 57224
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 312
telemt_me_refill_failed_total 197
telemt_me_writer_restored_same_endpoint_total 755
telemt_me_writer_restored_fallback_total 46
telemt_me_async_recovery_trigger_total 59
telemt_me_writer_removed_unexpected_minus_restored_total 76
telemt_user_connections_total{user="hello"} 4193044
telemt_user_connections_current{user="hello"} 4171
telemt_user_octets_from_client{user="hello"} 79056173973 (73.63 GB)
telemt_user_octets_to_client{user="hello"} 1750548559644 (1.59 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1650
telemt_user_unique_ips_recent_window{user="hello"} 686
```