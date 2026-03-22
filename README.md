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

# Server Metrics 2026-03-22 23:34:19 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 95275.4 (26h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3397106
telemt_connections_bad_total 277097
telemt_connections_current 884
telemt_connections_me_current 884
telemt_handshake_timeouts_total 106856
telemt_upstream_connect_attempt_total 35115
telemt_upstream_connect_success_total 35114
telemt_upstream_connect_attempts_per_request{bucket="1"} 35114
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12138
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22845
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 91
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 450
telemt_me_reconnect_attempts_total 1363
telemt_me_reconnect_success_total 571
telemt_me_reader_eof_total 587
telemt_me_idle_close_by_peer_total 587
telemt_me_route_drop_no_conn_total 2970258
telemt_me_route_drop_channel_closed_total 1230
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2829436
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_endpoint_quarantine_total 653
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 740
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
telemt_me_writers_active_current 46
telemt_desync_total 12097
telemt_desync_full_logged_total 3799
telemt_desync_suppressed_total 8298
telemt_desync_frames_bucket_total{bucket="1_2"} 3249
telemt_desync_frames_bucket_total{bucket="3_10"} 4419
telemt_desync_frames_bucket_total{bucket="gt_10"} 4429
telemt_pool_swap_total 105
telemt_pool_force_close_total 3273
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 639
telemt_me_draining_writers_reap_progress_total 32146
telemt_me_writer_removed_unexpected_total 567
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2335
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 30025
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3217
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 56
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 28873
telemt_me_writer_teardown_success_total{mode="normal"} 32360
telemt_me_writer_teardown_noop_total 32157
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 51146
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 53401
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 55499
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 59422
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 62348
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 64029
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 64512
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 64517
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 64517
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 64517
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 64517
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 64517
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 64517
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 374.244731
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 64517
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 639
telemt_me_refill_failed_total 42
telemt_me_writer_restored_same_endpoint_total 510
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 56
telemt_user_connections_total{user="hello"} 2818707
telemt_user_connections_current{user="hello"} 884
telemt_user_octets_from_client{user="hello"} 40433671472 (37.66 GB)
telemt_user_octets_to_client{user="hello"} 767824552076 (715.09 GB)
telemt_user_unique_ips_current{user="hello"} 375
telemt_user_unique_ips_recent_window{user="hello"} 111
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 108641.1 (30h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3969269
telemt_connections_bad_total 360709
telemt_connections_current 415
telemt_connections_me_current 415
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 100185
telemt_upstream_connect_attempt_total 67209
telemt_upstream_connect_success_total 66398
telemt_upstream_connect_fail_total 719
telemt_upstream_connect_attempts_per_request{bucket="1"} 67117
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37193
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29001
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 204
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 719
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 9726
telemt_me_reconnect_success_total 3512
telemt_me_reader_eof_total 3521
telemt_me_idle_close_by_peer_total 3521
telemt_me_route_drop_no_conn_total 3637789
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3157084
telemt_me_endpoint_quarantine_total 825
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_outage_enter_total 41
telemt_me_single_endpoint_outage_exit_total 41
telemt_me_single_endpoint_outage_reconnect_attempt_total 41
telemt_me_single_endpoint_outage_reconnect_success_total 40
telemt_me_single_endpoint_quarantine_bypass_total 41
telemt_me_single_endpoint_shadow_rotate_total 844
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
telemt_me_writers_active_current 43
telemt_desync_total 12881
telemt_desync_full_logged_total 7219
telemt_desync_suppressed_total 5662
telemt_desync_frames_bucket_total{bucket="1_2"} 2915
telemt_desync_frames_bucket_total{bucket="3_10"} 5054
telemt_desync_frames_bucket_total{bucket="gt_10"} 4912
telemt_pool_swap_total 100
telemt_pool_force_close_total 2975
telemt_pool_stale_pick_total 6
telemt_me_writer_close_signal_drop_total 244
telemt_me_draining_writers_reap_progress_total 43958
telemt_me_writer_removed_unexpected_total 3456
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5958
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 41484
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2517
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 458
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 40983
telemt_me_writer_teardown_success_total{mode="normal"} 47442
telemt_me_writer_teardown_noop_total 43959
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 89442
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 90681
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 91015
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 91323
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 91386
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 91399
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 91401
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 91401
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 91401
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 91401
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 91401
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 91401
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 91401
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.544234
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 91401
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 244
telemt_me_refill_failed_total 238
telemt_me_writer_restored_same_endpoint_total 3158
telemt_me_writer_restored_fallback_total 28
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 270
telemt_user_connections_total{user="hello"} 3169571
telemt_user_connections_current{user="hello"} 415
telemt_user_octets_from_client{user="hello"} 42815824430 (39.88 GB)
telemt_user_octets_to_client{user="hello"} 785161134344 (731.24 GB)
telemt_user_msgs_from_client{user="hello"} 47428
telemt_user_msgs_to_client{user="hello"} 180951
telemt_user_unique_ips_current{user="hello"} 255
telemt_user_unique_ips_recent_window{user="hello"} 69
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 183500.9 (50h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16266010
telemt_connections_bad_total 1632182
telemt_connections_current 999
telemt_connections_me_current 999
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 396578
telemt_upstream_connect_attempt_total 81711
telemt_upstream_connect_success_total 81610
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 81627
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40194
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39705
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1704
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2935
telemt_me_reconnect_success_total 1531
telemt_me_reader_eof_total 1476
telemt_me_idle_close_by_peer_total 1474
telemt_me_route_drop_no_conn_total 14036684
telemt_me_route_drop_channel_closed_total 145
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12924340
telemt_me_endpoint_quarantine_total 1193
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1374
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 45
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 33
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 46
telemt_desync_total 53428
telemt_desync_full_logged_total 16956
telemt_desync_suppressed_total 36472
telemt_desync_frames_bucket_total{bucket="1_2"} 11873
telemt_desync_frames_bucket_total{bucket="3_10"} 20813
telemt_desync_frames_bucket_total{bucket="gt_10"} 20742
telemt_pool_swap_total 198
telemt_pool_force_close_total 6579
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 1051
telemt_me_draining_writers_reap_progress_total 61371
telemt_me_writer_removed_unexpected_total 1423
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5302
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 56764
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 45
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 6109
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 54792
telemt_me_writer_teardown_success_total{mode="normal"} 62066
telemt_me_writer_teardown_noop_total 61424
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 112435
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 115999
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 117771
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 120162
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 121829
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 122880
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 123451
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 123481
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 123482
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 123486
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 123488
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 123490
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 123490
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 317.418691
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 123490
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1051
telemt_me_refill_failed_total 77
telemt_me_writer_restored_same_endpoint_total 1324
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 91
telemt_user_connections_total{user="hello"} 12924553
telemt_user_connections_current{user="hello"} 999
telemt_user_octets_from_client{user="hello"} 190670356865 (177.58 GB)
telemt_user_octets_to_client{user="hello"} 3476769543475 (3.16 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 481
telemt_user_unique_ips_recent_window{user="hello"} 84
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 183502.3 (50h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11809452
telemt_connections_bad_total 1219451
telemt_connections_current 627
telemt_connections_me_current 627
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 344245
telemt_upstream_connect_attempt_total 96191
telemt_upstream_connect_success_total 94878
telemt_upstream_connect_fail_total 865
telemt_upstream_connect_attempts_per_request{bucket="1"} 95743
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 51261
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39632
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 188
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3797
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 865
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 225
telemt_me_reconnect_attempts_total 4350
telemt_me_reconnect_success_total 1837
telemt_me_reader_eof_total 1700
telemt_me_idle_close_by_peer_total 1700
telemt_me_route_drop_no_conn_total 4548558
telemt_me_route_drop_channel_closed_total 497
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8775107
telemt_me_endpoint_quarantine_total 1200
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1396
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 52
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
telemt_desync_total 38636
telemt_desync_full_logged_total 13003
telemt_desync_suppressed_total 25633
telemt_desync_frames_bucket_total{bucket="1_2"} 9554
telemt_desync_frames_bucket_total{bucket="3_10"} 14847
telemt_desync_frames_bucket_total{bucket="gt_10"} 14235
telemt_pool_swap_total 195
telemt_pool_force_close_total 5940
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 706
telemt_me_draining_writers_reap_progress_total 59737
telemt_me_writer_removed_unexpected_total 1733
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5423
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 55900
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5428
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 512
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 53797
telemt_me_writer_teardown_success_total{mode="normal"} 61323
telemt_me_writer_teardown_noop_total 59762
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 114367
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 117565
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 118710
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 119901
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 120660
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 121000
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 121075
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 121077
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 121083
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 121085
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 121085
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 121085
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 121085
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 104.286742
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 121085
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 706
telemt_me_refill_failed_total 135
telemt_me_writer_restored_same_endpoint_total 1568
telemt_me_writer_restored_fallback_total 20
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 145
telemt_user_connections_total{user="hello"} 8712909
telemt_user_connections_current{user="hello"} 627
telemt_user_octets_from_client{user="hello"} 217527072464 (202.59 GB)
telemt_user_octets_to_client{user="hello"} 3945115064619 (3.59 TB)
telemt_user_msgs_from_client{user="hello"} 124042
telemt_user_msgs_to_client{user="hello"} 140191
telemt_user_unique_ips_current{user="hello"} 294
telemt_user_unique_ips_recent_window{user="hello"} 56
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 183466.3 (50h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11002878
telemt_connections_bad_total 963721
telemt_connections_current 523
telemt_connections_me_current 523
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 345222
telemt_upstream_connect_attempt_total 80282
telemt_upstream_connect_success_total 78729
telemt_upstream_connect_fail_total 205
telemt_upstream_connect_attempts_per_request{bucket="1"} 78934
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36325
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38031
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2015
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2358
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 205
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 1420
telemt_me_reconnect_attempts_total 5675
telemt_me_reconnect_success_total 2321
telemt_me_reader_eof_total 2061
telemt_me_idle_close_by_peer_total 2060
telemt_me_route_drop_no_conn_total 5330466
telemt_me_route_drop_channel_closed_total 383
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8323339
telemt_me_endpoint_quarantine_total 1280
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 38
telemt_me_single_endpoint_outage_reconnect_success_total 32
telemt_me_single_endpoint_quarantine_bypass_total 38
telemt_me_single_endpoint_shadow_rotate_total 1352
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 68
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
telemt_desync_total 37953
telemt_desync_full_logged_total 12581
telemt_desync_suppressed_total 25372
telemt_desync_frames_bucket_total{bucket="1_2"} 9587
telemt_desync_frames_bucket_total{bucket="3_10"} 14510
telemt_desync_frames_bucket_total{bucket="gt_10"} 13856
telemt_pool_swap_total 191
telemt_pool_force_close_total 5847
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 736
telemt_me_draining_writers_reap_progress_total 59928
telemt_me_writer_removed_unexpected_total 2215
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6152
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 55919
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5276
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 571
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 54081
telemt_me_writer_teardown_success_total{mode="normal"} 62071
telemt_me_writer_teardown_noop_total 59999
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 116252
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 118963
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 119915
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 120988
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 121589
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 121803
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 121931
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 121962
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 121970
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 121983
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 122016
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 122019
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 122070
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3174.656695
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 122070
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 736
telemt_me_refill_failed_total 178
telemt_me_writer_restored_same_endpoint_total 2012
telemt_me_writer_restored_fallback_total 16
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 187
telemt_user_connections_total{user="hello"} 8315324
telemt_user_connections_current{user="hello"} 523
telemt_user_octets_from_client{user="hello"} 192373857383 (179.16 GB)
telemt_user_octets_to_client{user="hello"} 3458250191569 (3.15 TB)
telemt_user_msgs_from_client{user="hello"} 46587
telemt_user_msgs_to_client{user="hello"} 113900
telemt_user_unique_ips_current{user="hello"} 232
telemt_user_unique_ips_recent_window{user="hello"} 56
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 53746.7 (14h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11152713
telemt_connections_bad_total 667717
telemt_connections_current 1034
telemt_connections_me_current 1034
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 260723
telemt_upstream_connect_attempt_total 54556
telemt_upstream_connect_success_total 51744
telemt_upstream_connect_fail_total 1895
telemt_upstream_connect_attempts_per_request{bucket="1"} 53639
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26759
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17467
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6001
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1895
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 7404
telemt_me_reconnect_success_total 1135
telemt_me_reader_eof_total 707
telemt_me_idle_close_by_peer_total 706
telemt_me_route_drop_no_conn_total 25275020
telemt_me_route_drop_channel_closed_total 58
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9263474
telemt_me_endpoint_quarantine_total 385
telemt_me_single_endpoint_outage_enter_total 85
telemt_me_single_endpoint_outage_exit_total 85
telemt_me_single_endpoint_outage_reconnect_attempt_total 158
telemt_me_single_endpoint_outage_reconnect_success_total 42
telemt_me_single_endpoint_quarantine_bypass_total 158
telemt_me_single_endpoint_shadow_rotate_total 426
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
telemt_desync_total 16113
telemt_desync_full_logged_total 4341
telemt_desync_suppressed_total 11772
telemt_desync_frames_bucket_total{bucket="1_2"} 3068
telemt_desync_frames_bucket_total{bucket="3_10"} 6525
telemt_desync_frames_bucket_total{bucket="gt_10"} 6520
telemt_pool_swap_total 55
telemt_pool_force_close_total 1871
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 469
telemt_me_draining_writers_reap_progress_total 16349
telemt_me_writer_removed_unexpected_total 1024
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2273
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15040
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1564
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 307
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14478
telemt_me_writer_teardown_success_total{mode="normal"} 17313
telemt_me_writer_teardown_noop_total 16368
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 29816
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 31551
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 32260
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 33136
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 33502
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 33625
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 33681
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 33681
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 33681
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 33681
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 33681
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 33681
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 33681
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 53.501366
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 33681
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 469
telemt_me_refill_failed_total 334
telemt_me_writer_restored_same_endpoint_total 733
telemt_me_writer_restored_fallback_total 8
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3149
telemt_me_writer_removed_unexpected_minus_restored_total 283
telemt_user_connections_total{user="hello"} 9288968
telemt_user_connections_current{user="hello"} 1034
telemt_user_octets_from_client{user="hello"} 86393905402 (80.46 GB)
telemt_user_octets_to_client{user="hello"} 587311605677 (546.98 GB)
telemt_user_msgs_from_client{user="hello"} 67224
telemt_user_msgs_to_client{user="hello"} 56168
telemt_user_unique_ips_current{user="hello"} 430
telemt_user_unique_ips_recent_window{user="hello"} 97
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 183472.9 (50h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10939594
telemt_connections_bad_total 940113
telemt_connections_current 731
telemt_connections_me_current 731
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 241563
telemt_upstream_connect_attempt_total 109118
telemt_upstream_connect_success_total 107988
telemt_upstream_connect_fail_total 958
telemt_upstream_connect_attempts_per_request{bucket="1"} 108946
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 64849
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 41545
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1356
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 958
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 72788
telemt_me_reconnect_success_total 2999
telemt_me_reader_eof_total 2691
telemt_me_idle_close_by_peer_total 2689
telemt_me_route_drop_no_conn_total 5252174
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8632829
telemt_me_endpoint_quarantine_total 1220
telemt_me_single_endpoint_outage_enter_total 41
telemt_me_single_endpoint_outage_exit_total 41
telemt_me_single_endpoint_outage_reconnect_attempt_total 43
telemt_me_single_endpoint_outage_reconnect_success_total 41
telemt_me_single_endpoint_quarantine_bypass_total 43
telemt_me_single_endpoint_shadow_rotate_total 1381
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 53
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
telemt_desync_total 46056
telemt_desync_full_logged_total 15767
telemt_desync_suppressed_total 30289
telemt_desync_frames_bucket_total{bucket="1_2"} 9349
telemt_desync_frames_bucket_total{bucket="3_10"} 17629
telemt_desync_frames_bucket_total{bucket="gt_10"} 19078
telemt_pool_swap_total 187
telemt_pool_force_close_total 5542
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 659
telemt_me_draining_writers_reap_progress_total 64053
telemt_me_writer_removed_unexpected_total 2722
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6648
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 60160
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4793
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 749
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 58511
telemt_me_writer_teardown_success_total{mode="normal"} 66808
telemt_me_writer_teardown_noop_total 64054
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 128728
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 130126
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 130545
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 130818
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 130852
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 130855
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 130855
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 130858
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 130862
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 130862
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 130862
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 130862
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 130862
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.200986
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 130862
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 659
telemt_me_refill_failed_total 4297
telemt_me_writer_restored_same_endpoint_total 2530
telemt_me_writer_restored_fallback_total 48
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7367
telemt_me_writer_removed_unexpected_minus_restored_total 144
telemt_user_connections_total{user="hello"} 8635886
telemt_user_connections_current{user="hello"} 731
telemt_user_octets_from_client{user="hello"} 194160848645 (180.83 GB)
telemt_user_octets_to_client{user="hello"} 3297800363312 (3.00 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 357
telemt_user_unique_ips_recent_window{user="hello"} 62
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 120309.1 (33h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11627535
telemt_connections_bad_total 475144
telemt_connections_current 549
telemt_connections_me_current 549
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4753944
telemt_upstream_connect_attempt_total 57351
telemt_upstream_connect_success_total 56931
telemt_upstream_connect_fail_total 409
telemt_upstream_connect_attempts_per_request{bucket="1"} 57340
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30702
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26018
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 211
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 409
telemt_me_reconnect_attempts_total 48783
telemt_me_reconnect_success_total 1763
telemt_me_reader_eof_total 1432
telemt_me_idle_close_by_peer_total 1431
telemt_me_route_drop_no_conn_total 4079728
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5586430
telemt_me_endpoint_quarantine_total 795
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 918
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
telemt_me_writers_active_current 43
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 31388
telemt_desync_full_logged_total 10696
telemt_desync_suppressed_total 20692
telemt_desync_frames_bucket_total{bucket="1_2"} 6236
telemt_desync_frames_bucket_total{bucket="3_10"} 12379
telemt_desync_frames_bucket_total{bucket="gt_10"} 12773
telemt_pool_swap_total 127
telemt_pool_force_close_total 3784
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 373
telemt_me_draining_writers_reap_progress_total 43178
telemt_me_writer_removed_unexpected_total 1483
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3643
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 41061
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3343
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 441
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 39394
telemt_me_writer_teardown_success_total{mode="normal"} 44704
telemt_me_writer_teardown_noop_total 43185
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 86610
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 87352
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 87662
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 87889
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 87889
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 87889
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 87889
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 87889
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 87889
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 87889
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 87889
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 87889
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 87889
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.647493
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 87889
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 373
telemt_me_refill_failed_total 2732
telemt_me_writer_restored_same_endpoint_total 1567
telemt_me_writer_restored_fallback_total 21
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5579027
telemt_user_connections_current{user="hello"} 549
telemt_user_octets_from_client{user="hello"} 118824884656 (110.66 GB)
telemt_user_octets_to_client{user="hello"} 2160044134006 (1.96 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 273
telemt_user_unique_ips_recent_window{user="hello"} 67
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 101280.0 (28h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1488226
telemt_connections_bad_total 36476
telemt_connections_current 469
telemt_connections_me_current 469
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 29669
telemt_upstream_connect_attempt_total 47329
telemt_upstream_connect_success_total 47178
telemt_upstream_connect_fail_total 123
telemt_upstream_connect_attempts_per_request{bucket="1"} 47301
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21465
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24934
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 779
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 123
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2157
telemt_me_reconnect_success_total 875
telemt_me_reader_eof_total 855
telemt_me_idle_close_by_peer_total 855
telemt_me_route_drop_no_conn_total 510926
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1321614
telemt_me_endpoint_quarantine_total 819
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 837
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
telemt_me_writers_active_current 44
telemt_desync_total 8470
telemt_desync_full_logged_total 2532
telemt_desync_suppressed_total 5938
telemt_desync_frames_bucket_total{bucket="1_2"} 2203
telemt_desync_frames_bucket_total{bucket="3_10"} 3264
telemt_desync_frames_bucket_total{bucket="gt_10"} 3003
telemt_pool_swap_total 109
telemt_pool_force_close_total 2828
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 159
telemt_me_draining_writers_reap_progress_total 39808
telemt_me_writer_removed_unexpected_total 827
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3114
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 37556
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2740
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 36980
telemt_me_writer_teardown_success_total{mode="normal"} 40670
telemt_me_writer_teardown_noop_total 39812
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 79555
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 80215
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 80445
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 80482
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 80482
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 80482
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 80482
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 80482
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 80482
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 80482
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 80482
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 80482
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 80482
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.094883
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 80482
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 159
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 742
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 66
telemt_user_connections_total{user="hello"} 1317470
telemt_user_connections_current{user="hello"} 469
telemt_user_octets_from_client{user="hello"} 25713010453 (23.95 GB)
telemt_user_octets_to_client{user="hello"} 567251800915 (528.29 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 200
telemt_user_unique_ips_recent_window{user="hello"} 60
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 183477.5 (50h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13256188
telemt_connections_bad_total 1574540
telemt_connections_current 617
telemt_connections_me_current 617
telemt_handshake_timeouts_total 383392
telemt_upstream_connect_attempt_total 70953
telemt_upstream_connect_success_total 70610
telemt_upstream_connect_fail_total 207
telemt_upstream_connect_attempts_per_request{bucket="1"} 70817
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34981
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35525
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 100
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 207
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2807
telemt_me_reconnect_success_total 1429
telemt_me_reader_eof_total 1409
telemt_me_idle_close_by_peer_total 1409
telemt_me_route_drop_no_conn_total 4477091
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 41
telemt_me_route_drop_queue_full_profile_total{profile="high"} 41
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10013787
telemt_me_endpoint_quarantine_total 1269
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1381
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 43
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
telemt_desync_total 41839
telemt_desync_full_logged_total 13661
telemt_desync_suppressed_total 28178
telemt_desync_frames_bucket_total{bucket="1_2"} 10062
telemt_desync_frames_bucket_total{bucket="3_10"} 15385
telemt_desync_frames_bucket_total{bucket="gt_10"} 16392
telemt_pool_swap_total 203
telemt_pool_force_close_total 5488
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 670
telemt_me_draining_writers_reap_progress_total 64039
telemt_me_writer_removed_unexpected_total 1351
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5116
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 60322
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5314
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 58551
telemt_me_writer_teardown_success_total{mode="normal"} 65438
telemt_me_writer_teardown_noop_total 64041
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 126888
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 128587
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 128970
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 129346
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 129466
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 129479
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 129479
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 129479
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 129479
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 129479
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 129479
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 129479
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 129479
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.699103
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 129479
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 670
telemt_me_refill_failed_total 74
telemt_me_writer_restored_same_endpoint_total 1254
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 81
telemt_user_connections_total{user="hello"} 9980526
telemt_user_connections_current{user="hello"} 617
telemt_user_octets_from_client{user="hello"} 194392583916 (181.04 GB)
telemt_user_octets_to_client{user="hello"} 4429348456680 (4.03 TB)
telemt_user_unique_ips_current{user="hello"} 292
telemt_user_unique_ips_recent_window{user="hello"} 63
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 183473.9 (50h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11552058
telemt_connections_bad_total 1325230
telemt_connections_current 620
telemt_connections_me_current 620
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 307550
telemt_upstream_connect_attempt_total 97599
telemt_upstream_connect_success_total 96732
telemt_upstream_connect_fail_total 659
telemt_upstream_connect_attempts_per_request{bucket="1"} 97391
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 52633
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 41119
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2067
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 659
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 10225
telemt_me_reconnect_success_total 2510
telemt_me_reader_eof_total 2331
telemt_me_idle_close_by_peer_total 2330
telemt_me_seq_mismatch_total 90
telemt_me_route_drop_no_conn_total 5637507
telemt_me_route_drop_channel_closed_total 354
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8918014
telemt_me_endpoint_quarantine_total 1446
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 50
telemt_me_single_endpoint_outage_exit_total 50
telemt_me_single_endpoint_outage_reconnect_attempt_total 50
telemt_me_single_endpoint_outage_reconnect_success_total 48
telemt_me_single_endpoint_quarantine_bypass_total 50
telemt_me_single_endpoint_shadow_rotate_total 1384
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
telemt_me_writers_active_current 51
telemt_desync_total 41583
telemt_desync_full_logged_total 13358
telemt_desync_suppressed_total 28225
telemt_desync_frames_bucket_total{bucket="1_2"} 10722
telemt_desync_frames_bucket_total{bucket="3_10"} 15288
telemt_desync_frames_bucket_total{bucket="gt_10"} 15573
telemt_pool_swap_total 193
telemt_pool_force_close_total 5279
telemt_pool_stale_pick_total 360
telemt_me_writer_close_signal_drop_total 656
telemt_me_draining_writers_reap_progress_total 63988
telemt_me_writer_removed_unexpected_total 2368
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6474
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 59964
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4808
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 58709
telemt_me_writer_teardown_success_total{mode="normal"} 66438
telemt_me_writer_teardown_noop_total 63993
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 127745
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 129523
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 130062
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 130381
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 130431
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 130431
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 130431
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 130431
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 130431
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 130431
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 130431
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 130431
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 130431
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.408741
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 130431
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 656
telemt_me_refill_failed_total 399
telemt_me_writer_restored_same_endpoint_total 2030
telemt_me_writer_restored_fallback_total 124
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 135
telemt_me_writer_removed_unexpected_minus_restored_total 214
telemt_user_connections_total{user="hello"} 8923367
telemt_user_connections_current{user="hello"} 620
telemt_user_octets_from_client{user="hello"} 157054509309 (146.27 GB)
telemt_user_octets_to_client{user="hello"} 3472341006503 (3.16 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 287
telemt_user_unique_ips_recent_window{user="hello"} 60
```