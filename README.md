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

# Server Metrics 2026-03-23 04:24:15 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 112671.5 (31h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3839594
telemt_connections_bad_total 377242
telemt_connections_current 1305
telemt_connections_me_current 1305
telemt_handshake_timeouts_total 128159
telemt_upstream_connect_attempt_total 42026
telemt_upstream_connect_success_total 42025
telemt_upstream_connect_attempts_per_request{bucket="1"} 42025
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14581
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27307
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 94
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 451
telemt_me_reconnect_attempts_total 1461
telemt_me_reconnect_success_total 659
telemt_me_reader_eof_total 676
telemt_me_idle_close_by_peer_total 676
telemt_me_route_drop_no_conn_total 3035676
telemt_me_route_drop_channel_closed_total 1242
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3126913
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_endpoint_quarantine_total 803
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 880
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
telemt_me_writers_active_current 44
telemt_desync_total 13395
telemt_desync_full_logged_total 4271
telemt_desync_suppressed_total 9124
telemt_desync_frames_bucket_total{bucket="1_2"} 3524
telemt_desync_frames_bucket_total{bucket="3_10"} 4919
telemt_desync_frames_bucket_total{bucket="gt_10"} 4952
telemt_pool_swap_total 125
telemt_pool_force_close_total 3776
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 692
telemt_me_draining_writers_reap_progress_total 38469
telemt_me_writer_removed_unexpected_total 652
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2752
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 35999
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3714
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 62
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 34693
telemt_me_writer_teardown_success_total{mode="normal"} 38751
telemt_me_writer_teardown_noop_total 38481
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 63249
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 65711
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 67919
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 72010
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 75012
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 76714
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 77227
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 77232
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 77232
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 77232
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 77232
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 77232
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 77232
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 386.389518
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 77232
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 692
telemt_me_refill_failed_total 42
telemt_me_writer_restored_same_endpoint_total 592
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 59
telemt_user_connections_total{user="hello"} 3115439
telemt_user_connections_current{user="hello"} 1305
telemt_user_octets_from_client{user="hello"} 43850748860 (40.84 GB)
telemt_user_octets_to_client{user="hello"} 848929457064 (790.63 GB)
telemt_user_unique_ips_current{user="hello"} 526
telemt_user_unique_ips_recent_window{user="hello"} 230
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 126037.8 (35h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4090807
telemt_connections_bad_total 381585
telemt_connections_current 756
telemt_connections_me_current 756
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 103278
telemt_upstream_connect_attempt_total 78841
telemt_upstream_connect_success_total 77906
telemt_upstream_connect_fail_total 828
telemt_upstream_connect_attempts_per_request{bucket="1"} 78734
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43280
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34406
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 220
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 828
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 10653
telemt_me_reconnect_success_total 3790
telemt_me_reader_eof_total 3771
telemt_me_idle_close_by_peer_total 3771
telemt_me_route_drop_no_conn_total 3656126
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3247437
telemt_me_endpoint_quarantine_total 1016
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_outage_enter_total 51
telemt_me_single_endpoint_outage_exit_total 51
telemt_me_single_endpoint_outage_reconnect_attempt_total 52
telemt_me_single_endpoint_outage_reconnect_success_total 50
telemt_me_single_endpoint_quarantine_bypass_total 52
telemt_me_single_endpoint_shadow_rotate_total 990
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 44
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
telemt_me_writers_warm_current 7
telemt_desync_total 13319
telemt_desync_full_logged_total 7493
telemt_desync_suppressed_total 5826
telemt_desync_frames_bucket_total{bucket="1_2"} 3032
telemt_desync_frames_bucket_total{bucket="3_10"} 5231
telemt_desync_frames_bucket_total{bucket="gt_10"} 5056
telemt_pool_swap_total 119
telemt_pool_force_close_total 3292
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 258
telemt_me_draining_writers_reap_progress_total 52548
telemt_me_writer_removed_unexpected_total 3694
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6661
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 49621
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2834
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 458
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 49256
telemt_me_writer_teardown_success_total{mode="normal"} 56282
telemt_me_writer_teardown_noop_total 52549
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 106857
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 108109
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 108445
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 108753
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 108816
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 108829
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 108831
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 108831
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 108831
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 108831
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 108831
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 108831
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 108831
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.757256
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 108831
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 258
telemt_me_refill_failed_total 270
telemt_me_writer_restored_same_endpoint_total 3356
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 307
telemt_user_connections_total{user="hello"} 3261909
telemt_user_connections_current{user="hello"} 756
telemt_user_octets_from_client{user="hello"} 43811275367 (40.80 GB)
telemt_user_octets_to_client{user="hello"} 815952856713 (759.92 GB)
telemt_user_msgs_from_client{user="hello"} 52128
telemt_user_msgs_to_client{user="hello"} 188269
telemt_user_unique_ips_current{user="hello"} 442
telemt_user_unique_ips_recent_window{user="hello"} 204
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 200897.6 (55h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16539394
telemt_connections_bad_total 1676799
telemt_connections_current 1150
telemt_connections_me_current 1150
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 402900
telemt_upstream_connect_attempt_total 90513
telemt_upstream_connect_success_total 90406
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 90423
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44079
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 44590
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1730
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 3119
telemt_me_reconnect_success_total 1660
telemt_me_reader_eof_total 1615
telemt_me_idle_close_by_peer_total 1613
telemt_me_route_drop_no_conn_total 14083477
telemt_me_route_drop_channel_closed_total 145
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 13134114
telemt_me_endpoint_quarantine_total 1363
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1519
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
telemt_me_writers_active_current 44
telemt_desync_total 54645
telemt_desync_full_logged_total 17424
telemt_desync_suppressed_total 37221
telemt_desync_frames_bucket_total{bucket="1_2"} 12195
telemt_desync_frames_bucket_total{bucket="3_10"} 21376
telemt_desync_frames_bucket_total{bucket="gt_10"} 21074
telemt_pool_swap_total 218
telemt_pool_force_close_total 7021
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 1088
telemt_me_draining_writers_reap_progress_total 69474
telemt_me_writer_removed_unexpected_total 1551
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5836
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 64472
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 45
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 6551
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 62453
telemt_me_writer_teardown_success_total{mode="normal"} 70308
telemt_me_writer_teardown_noop_total 69527
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 128555
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 132318
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 134111
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 136507
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 138174
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 139225
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 139796
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 139826
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 139827
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 139831
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 139833
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 139835
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 139835
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 318.322709
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 139835
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1088
telemt_me_refill_failed_total 80
telemt_me_writer_restored_same_endpoint_total 1442
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 101
telemt_user_connections_total{user="hello"} 13134074
telemt_user_connections_current{user="hello"} 1150
telemt_user_octets_from_client{user="hello"} 198992587909 (185.33 GB)
telemt_user_octets_to_client{user="hello"} 3555733031199 (3.23 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 458
telemt_user_unique_ips_recent_window{user="hello"} 416
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 200899.1 (55h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12075663
telemt_connections_bad_total 1277939
telemt_connections_current 671
telemt_connections_me_current 671
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 347884
telemt_upstream_connect_attempt_total 104757
telemt_upstream_connect_success_total 103407
telemt_upstream_connect_fail_total 891
telemt_upstream_connect_attempts_per_request{bucket="1"} 104298
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 54945
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 44469
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 188
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3805
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 891
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 226
telemt_me_reconnect_attempts_total 4592
telemt_me_reconnect_success_total 1969
telemt_me_reader_eof_total 1836
telemt_me_idle_close_by_peer_total 1836
telemt_me_route_drop_no_conn_total 4582208
telemt_me_route_drop_channel_closed_total 498
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8934905
telemt_me_endpoint_quarantine_total 1374
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1538
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
telemt_me_writers_active_current 43
telemt_desync_total 39279
telemt_desync_full_logged_total 13230
telemt_desync_suppressed_total 26049
telemt_desync_frames_bucket_total{bucket="1_2"} 9734
telemt_desync_frames_bucket_total{bucket="3_10"} 15099
telemt_desync_frames_bucket_total{bucket="gt_10"} 14446
telemt_pool_swap_total 215
telemt_pool_force_close_total 6365
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 717
telemt_me_draining_writers_reap_progress_total 67536
telemt_me_writer_removed_unexpected_total 1863
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5917
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 63341
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5853
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 512
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 61171
telemt_me_writer_teardown_success_total{mode="normal"} 69258
telemt_me_writer_teardown_noop_total 67561
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 130048
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 133295
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 134444
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 135635
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 136394
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 136734
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 136809
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 136811
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 136817
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 136819
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 136819
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 136819
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 136819
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 104.594974
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 136819
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 717
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 1685
telemt_me_writer_restored_fallback_total 20
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 158
telemt_user_connections_total{user="hello"} 8872557
telemt_user_connections_current{user="hello"} 671
telemt_user_octets_from_client{user="hello"} 218855547332 (203.83 GB)
telemt_user_octets_to_client{user="hello"} 4002687422195 (3.64 TB)
telemt_user_msgs_from_client{user="hello"} 124042
telemt_user_msgs_to_client{user="hello"} 140191
telemt_user_unique_ips_current{user="hello"} 259
telemt_user_unique_ips_recent_window{user="hello"} 255
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 200863.1 (55h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11216744
telemt_connections_bad_total 1012379
telemt_connections_current 960
telemt_connections_me_current 960
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 349345
telemt_upstream_connect_attempt_total 89253
telemt_upstream_connect_success_total 87682
telemt_upstream_connect_fail_total 205
telemt_upstream_connect_attempts_per_request{bucket="1"} 87887
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40207
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 43045
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2062
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2368
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 205
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 1420
telemt_me_reconnect_attempts_total 5868
telemt_me_reconnect_success_total 2458
telemt_me_reader_eof_total 2205
telemt_me_idle_close_by_peer_total 2204
telemt_me_route_drop_no_conn_total 5360357
telemt_me_route_drop_channel_closed_total 384
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8450368
telemt_me_endpoint_quarantine_total 1422
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 38
telemt_me_single_endpoint_outage_reconnect_success_total 32
telemt_me_single_endpoint_quarantine_bypass_total 38
telemt_me_single_endpoint_shadow_rotate_total 1497
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 71
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
telemt_me_writers_active_current 42
telemt_desync_total 38501
telemt_desync_full_logged_total 12773
telemt_desync_suppressed_total 25728
telemt_desync_frames_bucket_total{bucket="1_2"} 9719
telemt_desync_frames_bucket_total{bucket="3_10"} 14746
telemt_desync_frames_bucket_total{bucket="gt_10"} 14036
telemt_pool_swap_total 211
telemt_pool_force_close_total 6232
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 755
telemt_me_draining_writers_reap_progress_total 68094
telemt_me_writer_removed_unexpected_total 2351
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6673
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 63708
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5661
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 571
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 61862
telemt_me_writer_teardown_success_total{mode="normal"} 70381
telemt_me_writer_teardown_noop_total 68165
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 132699
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 135428
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 136391
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 137464
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 138065
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 138279
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 138407
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 138438
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 138446
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 138459
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 138492
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 138495
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 138546
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3174.914097
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 138546
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 755
telemt_me_refill_failed_total 181
telemt_me_writer_restored_same_endpoint_total 2140
telemt_me_writer_restored_fallback_total 17
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 194
telemt_user_connections_total{user="hello"} 8442258
telemt_user_connections_current{user="hello"} 960
telemt_user_octets_from_client{user="hello"} 193529229235 (180.24 GB)
telemt_user_octets_to_client{user="hello"} 3507161904113 (3.19 TB)
telemt_user_msgs_from_client{user="hello"} 46587
telemt_user_msgs_to_client{user="hello"} 113900
telemt_user_unique_ips_current{user="hello"} 430
telemt_user_unique_ips_recent_window{user="hello"} 173
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 71143.3 (19h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11495392
telemt_connections_bad_total 674822
telemt_connections_current 1593
telemt_connections_me_current 1593
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 301735
telemt_upstream_connect_attempt_total 64435
telemt_upstream_connect_success_total 61031
telemt_upstream_connect_fail_total 2206
telemt_upstream_connect_attempts_per_request{bucket="1"} 63237
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31428
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22053
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6033
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2206
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 8247
telemt_me_reconnect_success_total 1445
telemt_me_reader_eof_total 928
telemt_me_idle_close_by_peer_total 927
telemt_me_route_drop_no_conn_total 25335434
telemt_me_route_drop_channel_closed_total 59
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9527373
telemt_me_endpoint_quarantine_total 547
telemt_me_single_endpoint_outage_enter_total 102
telemt_me_single_endpoint_outage_exit_total 102
telemt_me_single_endpoint_outage_reconnect_attempt_total 200
telemt_me_single_endpoint_outage_reconnect_success_total 50
telemt_me_single_endpoint_quarantine_bypass_total 200
telemt_me_single_endpoint_shadow_rotate_total 569
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
telemt_me_writers_active_current 44
telemt_me_writers_warm_current 11
telemt_desync_total 16964
telemt_desync_full_logged_total 4684
telemt_desync_suppressed_total 12280
telemt_desync_frames_bucket_total{bucket="1_2"} 3269
telemt_desync_frames_bucket_total{bucket="3_10"} 6923
telemt_desync_frames_bucket_total{bucket="gt_10"} 6772
telemt_pool_swap_total 73
telemt_pool_force_close_total 2286
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 511
telemt_me_draining_writers_reap_progress_total 23460
telemt_me_writer_removed_unexpected_total 1322
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3025
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21708
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1964
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 322
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21174
telemt_me_writer_teardown_success_total{mode="normal"} 24733
telemt_me_writer_teardown_noop_total 23479
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 44126
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 46021
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 46775
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 47667
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 48033
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 48156
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 48212
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 48212
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 48212
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 48212
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 48212
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 48212
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 48212
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 54.601744
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 48212
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 511
telemt_me_refill_failed_total 348
telemt_me_writer_restored_same_endpoint_total 936
telemt_me_writer_restored_fallback_total 16
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3153
telemt_me_writer_removed_unexpected_minus_restored_total 370
telemt_user_connections_total{user="hello"} 9553814
telemt_user_connections_current{user="hello"} 1593
telemt_user_octets_from_client{user="hello"} 89538411374 (83.39 GB)
telemt_user_octets_to_client{user="hello"} 676149037433 (629.71 GB)
telemt_user_msgs_from_client{user="hello"} 69581
telemt_user_msgs_to_client{user="hello"} 60103
telemt_user_unique_ips_current{user="hello"} 613
telemt_user_unique_ips_recent_window{user="hello"} 198
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 200869.7 (55h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11180606
telemt_connections_bad_total 986482
telemt_connections_current 1195
telemt_connections_me_current 1195
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 246341
telemt_upstream_connect_attempt_total 118128
telemt_upstream_connect_success_total 116898
telemt_upstream_connect_fail_total 1053
telemt_upstream_connect_attempts_per_request{bucket="1"} 117951
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 68711
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 46575
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1374
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1053
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 73459
telemt_me_reconnect_success_total 3229
telemt_me_reader_eof_total 2924
telemt_me_idle_close_by_peer_total 2921
telemt_me_route_drop_no_conn_total 5294753
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8802800
telemt_me_endpoint_quarantine_total 1370
telemt_me_single_endpoint_outage_enter_total 44
telemt_me_single_endpoint_outage_exit_total 44
telemt_me_single_endpoint_outage_reconnect_attempt_total 46
telemt_me_single_endpoint_outage_reconnect_success_total 44
telemt_me_single_endpoint_quarantine_bypass_total 46
telemt_me_single_endpoint_shadow_rotate_total 1525
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 55
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
telemt_desync_total 46914
telemt_desync_full_logged_total 16111
telemt_desync_suppressed_total 30803
telemt_desync_frames_bucket_total{bucket="1_2"} 9521
telemt_desync_frames_bucket_total{bucket="3_10"} 17988
telemt_desync_frames_bucket_total{bucket="gt_10"} 19405
telemt_pool_swap_total 207
telemt_pool_force_close_total 5958
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 677
telemt_me_draining_writers_reap_progress_total 72113
telemt_me_writer_removed_unexpected_total 2942
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 7215
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 67886
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5209
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 749
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 66155
telemt_me_writer_teardown_success_total{mode="normal"} 75101
telemt_me_writer_teardown_noop_total 72114
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 145060
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 146479
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 146898
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 147171
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 147205
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 147208
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 147208
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 147211
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 147215
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 147215
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 147215
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 147215
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 147215
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.339261
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 147215
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 677
telemt_me_refill_failed_total 4320
telemt_me_writer_restored_same_endpoint_total 2719
telemt_me_writer_restored_fallback_total 54
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7369
telemt_me_writer_removed_unexpected_minus_restored_total 169
telemt_user_connections_total{user="hello"} 8805607
telemt_user_connections_current{user="hello"} 1195
telemt_user_octets_from_client{user="hello"} 197858663161 (184.27 GB)
telemt_user_octets_to_client{user="hello"} 3368630798368 (3.06 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 502
telemt_user_unique_ips_recent_window{user="hello"} 160
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 137706.0 (38h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11926224
telemt_connections_bad_total 491991
telemt_connections_current 969
telemt_connections_me_current 969
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4815358
telemt_upstream_connect_attempt_total 66963
telemt_upstream_connect_success_total 66486
telemt_upstream_connect_fail_total 464
telemt_upstream_connect_attempts_per_request{bucket="1"} 66950
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35070
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31177
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 239
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 464
telemt_me_reconnect_attempts_total 49239
telemt_me_reconnect_success_total 1938
telemt_me_reader_eof_total 1620
telemt_me_idle_close_by_peer_total 1619
telemt_me_route_drop_no_conn_total 4121011
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5731428
telemt_me_endpoint_quarantine_total 950
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 1060
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
telemt_me_writers_active_current 43
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 32231
telemt_desync_full_logged_total 11015
telemt_desync_suppressed_total 21216
telemt_desync_frames_bucket_total{bucket="1_2"} 6464
telemt_desync_frames_bucket_total{bucket="3_10"} 12707
telemt_desync_frames_bucket_total{bucket="gt_10"} 13060
telemt_pool_swap_total 146
telemt_pool_force_close_total 4151
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 389
telemt_me_draining_writers_reap_progress_total 51940
telemt_me_writer_removed_unexpected_total 1660
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4126
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 49528
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3707
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 444
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 47789
telemt_me_writer_teardown_success_total{mode="normal"} 53654
telemt_me_writer_teardown_noop_total 51947
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 104300
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 105064
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 105374
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 105601
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 105601
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 105601
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 105601
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 105601
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 105601
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 105601
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 105601
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 105601
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 105601
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.769329
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 105601
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 389
telemt_me_refill_failed_total 2748
telemt_me_writer_restored_same_endpoint_total 1714
telemt_me_writer_restored_fallback_total 30
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5723429
telemt_user_connections_current{user="hello"} 969
telemt_user_octets_from_client{user="hello"} 121089003396 (112.77 GB)
telemt_user_octets_to_client{user="hello"} 2231442884710 (2.03 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 399
telemt_user_unique_ips_recent_window{user="hello"} 131
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 118676.9 (32h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1628089
telemt_connections_bad_total 37188
telemt_connections_current 609
telemt_connections_me_current 609
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 33500
telemt_upstream_connect_attempt_total 56056
telemt_upstream_connect_success_total 55882
telemt_upstream_connect_fail_total 146
telemt_upstream_connect_attempts_per_request{bucket="1"} 56028
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26351
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28710
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 821
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 146
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2421
telemt_me_reconnect_success_total 983
telemt_me_reader_eof_total 977
telemt_me_idle_close_by_peer_total 977
telemt_me_route_drop_no_conn_total 543157
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1446918
telemt_me_endpoint_quarantine_total 1001
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 981
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 16
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
telemt_desync_total 10111
telemt_desync_full_logged_total 2849
telemt_desync_suppressed_total 7262
telemt_desync_frames_bucket_total{bucket="1_2"} 3205
telemt_desync_frames_bucket_total{bucket="3_10"} 3808
telemt_desync_frames_bucket_total{bucket="gt_10"} 3098
telemt_pool_swap_total 128
telemt_pool_force_close_total 3222
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 176
telemt_me_draining_writers_reap_progress_total 47771
telemt_me_writer_removed_unexpected_total 941
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3596
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 45159
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3134
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 44549
telemt_me_writer_teardown_success_total{mode="normal"} 48755
telemt_me_writer_teardown_noop_total 47775
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 95513
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 96263
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 96493
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 96530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 96530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 96530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 96530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 96530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 96530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 96530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 96530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 96530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 96530
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.555616
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 96530
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 176
telemt_me_refill_failed_total 80
telemt_me_writer_restored_same_endpoint_total 841
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 78
telemt_user_connections_total{user="hello"} 1442580
telemt_user_connections_current{user="hello"} 609
telemt_user_octets_from_client{user="hello"} 26959927465 (25.11 GB)
telemt_user_octets_to_client{user="hello"} 601512377939 (560.20 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 267
telemt_user_unique_ips_recent_window{user="hello"} 108
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 200874.3 (55h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13474363
telemt_connections_bad_total 1628297
telemt_connections_current 1210
telemt_connections_me_current 1210
telemt_handshake_timeouts_total 393965
telemt_upstream_connect_attempt_total 80816
telemt_upstream_connect_success_total 80456
telemt_upstream_connect_fail_total 223
telemt_upstream_connect_attempts_per_request{bucket="1"} 80679
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39796
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 40555
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 101
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 223
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 3165
telemt_me_reconnect_success_total 1599
telemt_me_reader_eof_total 1588
telemt_me_idle_close_by_peer_total 1588
telemt_me_route_drop_no_conn_total 4507678
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 42
telemt_me_route_drop_queue_full_profile_total{profile="high"} 42
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10155400
telemt_me_endpoint_quarantine_total 1482
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 13
telemt_me_single_endpoint_outage_exit_total 13
telemt_me_single_endpoint_outage_reconnect_attempt_total 14
telemt_me_single_endpoint_outage_reconnect_success_total 12
telemt_me_single_endpoint_quarantine_bypass_total 14
telemt_me_single_endpoint_shadow_rotate_total 1526
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 44
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
telemt_desync_total 42594
telemt_desync_full_logged_total 13906
telemt_desync_suppressed_total 28688
telemt_desync_frames_bucket_total{bucket="1_2"} 10370
telemt_desync_frames_bucket_total{bucket="3_10"} 15645
telemt_desync_frames_bucket_total{bucket="gt_10"} 16579
telemt_pool_swap_total 223
telemt_pool_force_close_total 5810
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 690
telemt_me_draining_writers_reap_progress_total 73143
telemt_me_writer_removed_unexpected_total 1520
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5644
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 69077
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5636
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 67333
telemt_me_writer_teardown_success_total{mode="normal"} 74721
telemt_me_writer_teardown_noop_total 73145
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 145245
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 146974
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 147357
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 147733
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 147853
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 147866
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 147866
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 147866
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 147866
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 147866
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 147866
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 147866
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 147866
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.900338
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 147866
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 690
telemt_me_refill_failed_total 84
telemt_me_writer_restored_same_endpoint_total 1408
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 95
telemt_user_connections_total{user="hello"} 10121973
telemt_user_connections_current{user="hello"} 1210
telemt_user_octets_from_client{user="hello"} 196019580216 (182.56 GB)
telemt_user_octets_to_client{user="hello"} 4507503813468 (4.10 TB)
telemt_user_unique_ips_current{user="hello"} 466
telemt_user_unique_ips_recent_window{user="hello"} 137
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 200871.0 (55h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11792183
telemt_connections_bad_total 1381722
telemt_connections_current 1057
telemt_connections_me_current 1057
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 316689
telemt_upstream_connect_attempt_total 108638
telemt_upstream_connect_success_total 107702
telemt_upstream_connect_fail_total 728
telemt_upstream_connect_attempts_per_request{bucket="1"} 108430
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 58500
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 46218
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2071
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 728
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 10977
telemt_me_reconnect_success_total 2726
telemt_me_reader_eof_total 2529
telemt_me_idle_close_by_peer_total 2528
telemt_me_seq_mismatch_total 105
telemt_me_route_drop_no_conn_total 5675461
telemt_me_route_drop_channel_closed_total 354
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9073793
telemt_me_endpoint_quarantine_total 1657
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 56
telemt_me_single_endpoint_outage_exit_total 56
telemt_me_single_endpoint_outage_reconnect_attempt_total 56
telemt_me_single_endpoint_outage_reconnect_success_total 54
telemt_me_single_endpoint_quarantine_bypass_total 56
telemt_me_single_endpoint_shadow_rotate_total 1531
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
telemt_me_writers_active_current 43
telemt_desync_total 42258
telemt_desync_full_logged_total 13609
telemt_desync_suppressed_total 28649
telemt_desync_frames_bucket_total{bucket="1_2"} 10984
telemt_desync_frames_bucket_total{bucket="3_10"} 15522
telemt_desync_frames_bucket_total{bucket="gt_10"} 15752
telemt_pool_swap_total 213
telemt_pool_force_close_total 5573
telemt_pool_stale_pick_total 390
telemt_me_writer_close_signal_drop_total 678
telemt_me_draining_writers_reap_progress_total 73454
telemt_me_writer_removed_unexpected_total 2564
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 7039
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 69078
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5102
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 67881
telemt_me_writer_teardown_success_total{mode="normal"} 76117
telemt_me_writer_teardown_noop_total 73459
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 146870
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 148668
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 149207
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 149526
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 149576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 149576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 149576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 149576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 149576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 149576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 149576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 149576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 149576
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.611942
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 149576
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 678
telemt_me_refill_failed_total 428
telemt_me_writer_restored_same_endpoint_total 2176
telemt_me_writer_restored_fallback_total 141
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 135
telemt_me_writer_removed_unexpected_minus_restored_total 247
telemt_user_connections_total{user="hello"} 9078318
telemt_user_connections_current{user="hello"} 1057
telemt_user_octets_from_client{user="hello"} 158548346932 (147.66 GB)
telemt_user_octets_to_client{user="hello"} 3549585432826 (3.23 TB)
telemt_user_msgs_from_client{user="hello"} 103592
telemt_user_msgs_to_client{user="hello"} 254638
telemt_user_unique_ips_current{user="hello"} 398
telemt_user_unique_ips_recent_window{user="hello"} 114
```