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

# Server Metrics 2026-03-22 17:15:22 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 72539.2 (20h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2617417
telemt_connections_bad_total 141145
telemt_connections_current 1561
telemt_connections_me_current 1561
telemt_handshake_timeouts_total 90623
telemt_upstream_connect_attempt_total 26736
telemt_upstream_connect_success_total 26735
telemt_upstream_connect_attempts_per_request{bucket="1"} 26735
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9301
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17351
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 60
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 150
telemt_me_reconnect_attempts_total 1085
telemt_me_reconnect_success_total 459
telemt_me_reader_eof_total 462
telemt_me_idle_close_by_peer_total 462
telemt_me_route_drop_no_conn_total 2189894
telemt_me_route_drop_channel_closed_total 888
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2233457
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_endpoint_quarantine_total 496
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 569
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
telemt_desync_total 10392
telemt_desync_full_logged_total 3287
telemt_desync_suppressed_total 7105
telemt_desync_frames_bucket_total{bucket="1_2"} 2782
telemt_desync_frames_bucket_total{bucket="3_10"} 3874
telemt_desync_frames_bucket_total{bucket="gt_10"} 3736
telemt_pool_swap_total 80
telemt_pool_force_close_total 2488
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 492
telemt_me_draining_writers_reap_progress_total 24433
telemt_me_writer_removed_unexpected_total 448
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1783
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22869
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2436
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 52
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21945
telemt_me_writer_teardown_success_total{mode="normal"} 24652
telemt_me_writer_teardown_noop_total 24439
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 39445
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 41250
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 42981
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 45938
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 47914
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 48809
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 49087
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 49091
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 49091
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 49091
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 49091
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 49091
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 49091
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 238.737354
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 49091
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 492
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 407
telemt_me_writer_removed_unexpected_minus_restored_total 41
telemt_user_connections_total{user="hello"} 2229767
telemt_user_connections_current{user="hello"} 1561
telemt_user_octets_from_client{user="hello"} 32953162116 (30.69 GB)
telemt_user_octets_to_client{user="hello"} 586429350732 (546.15 GB)
telemt_user_unique_ips_current{user="hello"} 604
telemt_user_unique_ips_recent_window{user="hello"} 225
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 85905.2 (23h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3656022
telemt_connections_bad_total 331200
telemt_connections_current 599
telemt_connections_me_current 599
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 91462
telemt_upstream_connect_attempt_total 53464
telemt_upstream_connect_success_total 52796
telemt_upstream_connect_fail_total 588
telemt_upstream_connect_attempts_per_request{bucket="1"} 53384
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30441
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22182
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 173
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 588
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 6213
telemt_me_reconnect_success_total 2257
telemt_me_reader_eof_total 2185
telemt_me_idle_close_by_peer_total 2185
telemt_me_route_drop_no_conn_total 3548493
telemt_me_route_drop_channel_closed_total 36
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2900131
telemt_me_endpoint_quarantine_total 687
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 39
telemt_me_single_endpoint_outage_exit_total 39
telemt_me_single_endpoint_outage_reconnect_attempt_total 39
telemt_me_single_endpoint_outage_reconnect_success_total 38
telemt_me_single_endpoint_quarantine_bypass_total 39
telemt_me_single_endpoint_shadow_rotate_total 664
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
telemt_desync_total 11403
telemt_desync_full_logged_total 6370
telemt_desync_suppressed_total 5033
telemt_desync_frames_bucket_total{bucket="1_2"} 2657
telemt_desync_frames_bucket_total{bucket="3_10"} 4468
telemt_desync_frames_bucket_total{bucket="gt_10"} 4278
telemt_pool_swap_total 81
telemt_pool_force_close_total 2430
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 205
telemt_me_draining_writers_reap_progress_total 34205
telemt_me_writer_removed_unexpected_total 2138
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4109
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 32242
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2070
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 360
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 31775
telemt_me_writer_teardown_success_total{mode="normal"} 36351
telemt_me_writer_teardown_noop_total 34205
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 68828
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 69911
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 70184
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 70490
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 70541
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 70554
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 70556
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 70556
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 70556
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 70556
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 70556
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 70556
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 70556
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 13.153531
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 70556
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 205
telemt_me_refill_failed_total 156
telemt_me_writer_restored_same_endpoint_total 1948
telemt_me_writer_restored_fallback_total 25
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 165
telemt_user_connections_total{user="hello"} 2911341
telemt_user_connections_current{user="hello"} 599
telemt_user_octets_from_client{user="hello"} 36679535375 (34.16 GB)
telemt_user_octets_to_client{user="hello"} 659489389242 (614.20 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 390
telemt_user_unique_ips_recent_window{user="hello"} 225
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 160765.1 (44h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15485909
telemt_connections_bad_total 1467352
telemt_connections_current 2521
telemt_connections_me_current 2521
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 378759
telemt_upstream_connect_attempt_total 72363
telemt_upstream_connect_success_total 72267
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 72284
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36275
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34309
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1676
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2698
telemt_me_reconnect_success_total 1387
telemt_me_reader_eof_total 1325
telemt_me_idle_close_by_peer_total 1323
telemt_me_route_drop_no_conn_total 13846473
telemt_me_route_drop_channel_closed_total 140
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12355688
telemt_me_endpoint_quarantine_total 1011
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1197
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
telemt_me_writers_active_current 45
telemt_desync_total 50511
telemt_desync_full_logged_total 15865
telemt_desync_suppressed_total 34646
telemt_desync_frames_bucket_total{bucket="1_2"} 11284
telemt_desync_frames_bucket_total{bucket="3_10"} 19724
telemt_desync_frames_bucket_total{bucket="gt_10"} 19503
telemt_pool_swap_total 173
telemt_pool_force_close_total 5877
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 950
telemt_me_draining_writers_reap_progress_total 52855
telemt_me_writer_removed_unexpected_total 1279
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4631
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 48794
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 42
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5417
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 460
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 46978
telemt_me_writer_teardown_success_total{mode="normal"} 53425
telemt_me_writer_teardown_noop_total 52905
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 96087
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 99369
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 100979
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 103158
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 104734
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 105733
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 106291
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 106321
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 106322
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 106326
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 106328
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 106330
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 106330
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 303.606196
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 106330
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 950
telemt_me_refill_failed_total 72
telemt_me_writer_restored_same_endpoint_total 1192
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 80
telemt_user_connections_total{user="hello"} 12356721
telemt_user_connections_current{user="hello"} 2521
telemt_user_octets_from_client{user="hello"} 176659616037 (164.53 GB)
telemt_user_octets_to_client{user="hello"} 3208862355183 (2.92 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 957
telemt_user_unique_ips_recent_window{user="hello"} 338
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 160766.6 (44h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11168356
telemt_connections_bad_total 1086035
telemt_connections_current 1521
telemt_connections_me_current 1521
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 333563
telemt_upstream_connect_attempt_total 84555
telemt_upstream_connect_success_total 83397
telemt_upstream_connect_fail_total 834
telemt_upstream_connect_attempts_per_request{bucket="1"} 84231
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 45394
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34150
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 157
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3696
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 834
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 182
telemt_me_reconnect_attempts_total 3960
telemt_me_reconnect_success_total 1623
telemt_me_reader_eof_total 1495
telemt_me_idle_close_by_peer_total 1495
telemt_me_route_drop_no_conn_total 4387114
telemt_me_route_drop_channel_closed_total 483
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8326656
telemt_me_endpoint_quarantine_total 1017
telemt_me_single_endpoint_outage_enter_total 27
telemt_me_single_endpoint_outage_exit_total 27
telemt_me_single_endpoint_outage_reconnect_attempt_total 32
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 32
telemt_me_single_endpoint_shadow_rotate_total 1216
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
telemt_me_writers_active_current 44
telemt_desync_total 37027
telemt_desync_full_logged_total 12447
telemt_desync_suppressed_total 24580
telemt_desync_frames_bucket_total{bucket="1_2"} 9094
telemt_desync_frames_bucket_total{bucket="3_10"} 14272
telemt_desync_frames_bucket_total{bucket="gt_10"} 13661
telemt_pool_swap_total 171
telemt_pool_force_close_total 5320
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 672
telemt_me_draining_writers_reap_progress_total 51166
telemt_me_writer_removed_unexpected_total 1523
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4709
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 47822
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4842
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 478
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 45846
telemt_me_writer_teardown_success_total{mode="normal"} 52531
telemt_me_writer_teardown_noop_total 51189
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 97383
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 100355
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 101446
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 102565
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 103304
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 103635
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 103710
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 103712
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 103718
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 103720
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 103720
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 103720
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 103720
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 100.755452
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 103720
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 672
telemt_me_refill_failed_total 126
telemt_me_writer_restored_same_endpoint_total 1384
telemt_me_writer_restored_fallback_total 15
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 124
telemt_user_connections_total{user="hello"} 8265232
telemt_user_connections_current{user="hello"} 1521
telemt_user_octets_from_client{user="hello"} 206587739149 (192.40 GB)
telemt_user_octets_to_client{user="hello"} 3725902734230 (3.39 TB)
telemt_user_msgs_from_client{user="hello"} 113340
telemt_user_msgs_to_client{user="hello"} 116189
telemt_user_unique_ips_current{user="hello"} 598
telemt_user_unique_ips_recent_window{user="hello"} 212
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 160730.7 (44h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10544833
telemt_connections_bad_total 909715
telemt_connections_current 1310
telemt_connections_me_current 1310
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 336980
telemt_upstream_connect_attempt_total 69831
telemt_upstream_connect_success_total 68841
telemt_upstream_connect_fail_total 182
telemt_upstream_connect_attempts_per_request{bucket="1"} 69023
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32678
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32699
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1375
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2089
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 182
telemt_me_keepalive_timeout_total 1383
telemt_me_reconnect_attempts_total 4760
telemt_me_reconnect_success_total 1923
telemt_me_reader_eof_total 1674
telemt_me_idle_close_by_peer_total 1673
telemt_me_route_drop_no_conn_total 5160666
telemt_me_route_drop_channel_closed_total 367
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7955658
telemt_me_endpoint_quarantine_total 1096
telemt_me_single_endpoint_outage_enter_total 32
telemt_me_single_endpoint_outage_exit_total 32
telemt_me_single_endpoint_outage_reconnect_attempt_total 33
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 33
telemt_me_single_endpoint_shadow_rotate_total 1183
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 56
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
telemt_desync_total 36529
telemt_desync_full_logged_total 12084
telemt_desync_suppressed_total 24445
telemt_desync_frames_bucket_total{bucket="1_2"} 9254
telemt_desync_frames_bucket_total{bucket="3_10"} 13967
telemt_desync_frames_bucket_total{bucket="gt_10"} 13308
telemt_pool_swap_total 168
telemt_pool_force_close_total 5242
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 687
telemt_me_draining_writers_reap_progress_total 51533
telemt_me_writer_removed_unexpected_total 1816
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5169
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 48093
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4700
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 542
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 46291
telemt_me_writer_teardown_success_total{mode="normal"} 53262
telemt_me_writer_teardown_noop_total 51604
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 99373
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 101888
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 102791
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 103816
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 104387
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 104599
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 104727
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 104758
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 104766
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 104779
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 104812
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 104815
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 104866
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3171.856434
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 104866
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 687
telemt_me_refill_failed_total 150
telemt_me_writer_restored_same_endpoint_total 1662
telemt_me_writer_restored_fallback_total 10
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 144
telemt_user_connections_total{user="hello"} 7948504
telemt_user_connections_current{user="hello"} 1310
telemt_user_octets_from_client{user="hello"} 183572366553 (170.97 GB)
telemt_user_octets_to_client{user="hello"} 3306684599781 (3.01 TB)
telemt_user_msgs_from_client{user="hello"} 46485
telemt_user_msgs_to_client{user="hello"} 113805
telemt_user_unique_ips_current{user="hello"} 508
telemt_user_unique_ips_recent_window{user="hello"} 153
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 31011.1 (8h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10318040
telemt_connections_bad_total 628948
telemt_connections_current 2088
telemt_connections_me_current 2088
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 198373
telemt_upstream_connect_attempt_total 40869
telemt_upstream_connect_success_total 38793
telemt_upstream_connect_fail_total 1478
telemt_upstream_connect_attempts_per_request{bucket="1"} 40271
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20045
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11444
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1389
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5915
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1478
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 6119
telemt_me_reconnect_success_total 779
telemt_me_reader_eof_total 479
telemt_me_idle_close_by_peer_total 479
telemt_me_route_drop_no_conn_total 25002186
telemt_me_route_drop_channel_closed_total 50
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8581598
telemt_me_endpoint_quarantine_total 194
telemt_me_single_endpoint_outage_enter_total 59
telemt_me_single_endpoint_outage_exit_total 59
telemt_me_single_endpoint_outage_reconnect_attempt_total 110
telemt_me_single_endpoint_outage_reconnect_success_total 32
telemt_me_single_endpoint_quarantine_bypass_total 110
telemt_me_single_endpoint_shadow_rotate_total 246
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 22
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
telemt_desync_total 13534
telemt_desync_full_logged_total 3510
telemt_desync_suppressed_total 10024
telemt_desync_frames_bucket_total{bucket="1_2"} 2466
telemt_desync_frames_bucket_total{bucket="3_10"} 5496
telemt_desync_frames_bucket_total{bucket="gt_10"} 5572
telemt_pool_swap_total 30
telemt_pool_force_close_total 1160
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 377
telemt_me_draining_writers_reap_progress_total 8644
telemt_me_writer_removed_unexpected_total 683
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1397
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 7891
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 878
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 282
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 7484
telemt_me_writer_teardown_success_total{mode="normal"} 9288
telemt_me_writer_teardown_noop_total 8649
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 15070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 16424
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 16902
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 17507
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 17786
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 17888
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 17937
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 17937
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 17937
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 17937
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 17937
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 17937
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 17937
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 40.832416
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 17937
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 377
telemt_me_refill_failed_total 295
telemt_me_writer_restored_same_endpoint_total 520
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 86
telemt_me_async_recovery_trigger_total 3059
telemt_me_writer_removed_unexpected_minus_restored_total 159
telemt_user_connections_total{user="hello"} 8603340
telemt_user_connections_current{user="hello"} 2088
telemt_user_octets_from_client{user="hello"} 68668633523 (63.95 GB)
telemt_user_octets_to_client{user="hello"} 345733767169 (321.99 GB)
telemt_user_msgs_from_client{user="hello"} 57283
telemt_user_msgs_to_client{user="hello"} 45481
telemt_user_unique_ips_current{user="hello"} 743
telemt_user_unique_ips_recent_window{user="hello"} 285
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 160737.2 (44h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10351985
telemt_connections_bad_total 870670
telemt_connections_current 1925
telemt_connections_me_current 1925
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 229345
telemt_upstream_connect_attempt_total 98616
telemt_upstream_connect_success_total 97594
telemt_upstream_connect_fail_total 869
telemt_upstream_connect_attempts_per_request{bucket="1"} 98463
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 60133
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35910
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1313
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 869
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 72084
telemt_me_reconnect_success_total 2659
telemt_me_reader_eof_total 2360
telemt_me_idle_close_by_peer_total 2358
telemt_me_route_drop_no_conn_total 5093925
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8165920
telemt_me_endpoint_quarantine_total 1084
telemt_me_single_endpoint_outage_enter_total 38
telemt_me_single_endpoint_outage_exit_total 38
telemt_me_single_endpoint_outage_reconnect_attempt_total 40
telemt_me_single_endpoint_outage_reconnect_success_total 38
telemt_me_single_endpoint_quarantine_bypass_total 40
telemt_me_single_endpoint_shadow_rotate_total 1199
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
telemt_me_writers_active_current 46
telemt_desync_total 42750
telemt_desync_full_logged_total 14577
telemt_desync_suppressed_total 28173
telemt_desync_frames_bucket_total{bucket="1_2"} 8694
telemt_desync_frames_bucket_total{bucket="3_10"} 16506
telemt_desync_frames_bucket_total{bucket="gt_10"} 17550
telemt_pool_swap_total 164
telemt_pool_force_close_total 4881
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 614
telemt_me_draining_writers_reap_progress_total 54688
telemt_me_writer_removed_unexpected_total 2402
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5849
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 51263
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4195
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 686
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 49807
telemt_me_writer_teardown_success_total{mode="normal"} 57112
telemt_me_writer_teardown_noop_total 54689
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 109788
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 111101
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 111485
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 111757
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 111791
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 111794
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 111794
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 111797
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 111801
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 111801
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 111801
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 111801
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 111801
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 16.579549
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 111801
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 614
telemt_me_refill_failed_total 4279
telemt_me_writer_restored_same_endpoint_total 2227
telemt_me_writer_restored_fallback_total 46
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7365
telemt_me_writer_removed_unexpected_minus_restored_total 129
telemt_user_connections_total{user="hello"} 8169709
telemt_user_connections_current{user="hello"} 1925
telemt_user_octets_from_client{user="hello"} 185051142937 (172.34 GB)
telemt_user_octets_to_client{user="hello"} 3083134218820 (2.80 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 685
telemt_user_unique_ips_recent_window{user="hello"} 240
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 97573.4 (27h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10799359
telemt_connections_bad_total 410848
telemt_connections_current 1697
telemt_connections_me_current 1697
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4512413
telemt_upstream_connect_attempt_total 46795
telemt_upstream_connect_success_total 46447
telemt_upstream_connect_fail_total 339
telemt_upstream_connect_attempts_per_request{bucket="1"} 46786
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25931
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20355
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 161
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 339
telemt_me_reconnect_attempts_total 48207
telemt_me_reconnect_success_total 1550
telemt_me_reader_eof_total 1209
telemt_me_idle_close_by_peer_total 1208
telemt_me_route_drop_no_conn_total 3947300
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5184067
telemt_me_endpoint_quarantine_total 634
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 58
telemt_me_single_endpoint_outage_reconnect_success_total 18
telemt_me_single_endpoint_quarantine_bypass_total 58
telemt_me_single_endpoint_shadow_rotate_total 735
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
telemt_me_writers_active_current 45
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 28633
telemt_desync_full_logged_total 9686
telemt_desync_suppressed_total 18947
telemt_desync_frames_bucket_total{bucket="1_2"} 5772
telemt_desync_frames_bucket_total{bucket="3_10"} 11284
telemt_desync_frames_bucket_total{bucket="gt_10"} 11577
telemt_pool_swap_total 103
telemt_pool_force_close_total 3164
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 329
telemt_me_draining_writers_reap_progress_total 33663
telemt_me_writer_removed_unexpected_total 1271
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3022
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 31943
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2743
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 421
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 30499
telemt_me_writer_teardown_success_total{mode="normal"} 34965
telemt_me_writer_teardown_noop_total 33670
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 67475
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 68143
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 68408
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 68635
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 68635
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 68635
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 68635
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 68635
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 68635
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 68635
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 68635
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 68635
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 68635
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.003016
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 68635
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 329
telemt_me_refill_failed_total 2712
telemt_me_writer_restored_same_endpoint_total 1378
telemt_me_writer_restored_fallback_total 15
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4330
telemt_user_connections_total{user="hello"} 5177365
telemt_user_connections_current{user="hello"} 1697
telemt_user_octets_from_client{user="hello"} 111803835348 (104.13 GB)
telemt_user_octets_to_client{user="hello"} 1960297151670 (1.78 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 631
telemt_user_unique_ips_recent_window{user="hello"} 241
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 78544.3 (21h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1091151
telemt_connections_bad_total 17004
telemt_connections_current 1227
telemt_connections_me_current 1227
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 20704
telemt_upstream_connect_attempt_total 38207
telemt_upstream_connect_success_total 38096
telemt_upstream_connect_fail_total 87
telemt_upstream_connect_attempts_per_request{bucket="1"} 38183
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17270
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20252
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 574
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 87
telemt_me_reconnect_attempts_total 1740
telemt_me_reconnect_success_total 732
telemt_me_reader_eof_total 707
telemt_me_idle_close_by_peer_total 707
telemt_me_route_drop_no_conn_total 380920
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 971475
telemt_me_endpoint_quarantine_total 669
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 648
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 15
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
telemt_desync_total 5508
telemt_desync_full_logged_total 1689
telemt_desync_suppressed_total 3819
telemt_desync_frames_bucket_total{bucket="1_2"} 1292
telemt_desync_frames_bucket_total{bucket="3_10"} 2177
telemt_desync_frames_bucket_total{bucket="gt_10"} 2039
telemt_pool_swap_total 84
telemt_pool_force_close_total 2148
telemt_me_writer_close_signal_drop_total 123
telemt_me_draining_writers_reap_progress_total 31680
telemt_me_writer_removed_unexpected_total 683
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2459
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 29930
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2065
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 83
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 29532
telemt_me_writer_teardown_success_total{mode="normal"} 32389
telemt_me_writer_teardown_noop_total 31683
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 63386
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 63877
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 64041
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 64072
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 64072
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 64072
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 64072
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 64072
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 64072
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 64072
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 64072
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 64072
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 64072
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.802662
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 64072
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 123
telemt_me_refill_failed_total 55
telemt_me_writer_restored_same_endpoint_total 623
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 967928
telemt_user_connections_current{user="hello"} 1227
telemt_user_octets_from_client{user="hello"} 17951513101 (16.72 GB)
telemt_user_octets_to_client{user="hello"} 419202056451 (390.41 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 412
telemt_user_unique_ips_recent_window{user="hello"} 177
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 160741.8 (44h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12632053
telemt_connections_bad_total 1467598
telemt_connections_current 2102
telemt_connections_me_current 2102
telemt_handshake_timeouts_total 350693
telemt_upstream_connect_attempt_total 60454
telemt_upstream_connect_success_total 60181
telemt_upstream_connect_fail_total 186
telemt_upstream_connect_attempts_per_request{bucket="1"} 60367
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29691
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30409
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 79
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 186
telemt_me_reconnect_attempts_total 2375
telemt_me_reconnect_success_total 1253
telemt_me_reader_eof_total 1218
telemt_me_idle_close_by_peer_total 1218
telemt_me_route_drop_no_conn_total 4219850
telemt_me_route_drop_channel_closed_total 121
telemt_me_route_drop_queue_full_total 37
telemt_me_route_drop_queue_full_profile_total{profile="high"} 37
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9553692
telemt_me_endpoint_quarantine_total 1077
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1201
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
telemt_desync_total 39245
telemt_desync_full_logged_total 12810
telemt_desync_suppressed_total 26435
telemt_desync_frames_bucket_total{bucket="1_2"} 9346
telemt_desync_frames_bucket_total{bucket="3_10"} 14536
telemt_desync_frames_bucket_total{bucket="gt_10"} 15363
telemt_pool_swap_total 178
telemt_pool_force_close_total 4913
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 627
telemt_me_draining_writers_reap_progress_total 54421
telemt_me_writer_removed_unexpected_total 1170
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4469
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 51156
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4739
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 49508
telemt_me_writer_teardown_success_total{mode="normal"} 55625
telemt_me_writer_teardown_noop_total 54423
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 107615
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 109225
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 109585
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 109915
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 110035
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 110048
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 110048
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 110048
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 110048
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 110048
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 110048
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 110048
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 110048
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 18.485074
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 110048
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 627
telemt_me_refill_failed_total 59
telemt_me_writer_restored_same_endpoint_total 1096
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 62
telemt_user_connections_total{user="hello"} 9522822
telemt_user_connections_current{user="hello"} 2102
telemt_user_octets_from_client{user="hello"} 186765288760 (173.94 GB)
telemt_user_octets_to_client{user="hello"} 4206949672384 (3.83 TB)
telemt_user_unique_ips_current{user="hello"} 731
telemt_user_unique_ips_recent_window{user="hello"} 278
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 160738.5 (44h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10951953
telemt_connections_bad_total 1222137
telemt_connections_current 1424
telemt_connections_me_current 1424
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 283331
telemt_upstream_connect_attempt_total 86263
telemt_upstream_connect_success_total 85555
telemt_upstream_connect_fail_total 571
telemt_upstream_connect_attempts_per_request{bucket="1"} 86126
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 47026
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35579
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 910
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2040
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 571
telemt_me_reconnect_attempts_total 9078
telemt_me_reconnect_success_total 2102
telemt_me_reader_eof_total 1958
telemt_me_idle_close_by_peer_total 1958
telemt_me_seq_mismatch_total 75
telemt_me_route_drop_no_conn_total 5468839
telemt_me_route_drop_channel_closed_total 351
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8473403
telemt_me_endpoint_quarantine_total 1222
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 42
telemt_me_single_endpoint_outage_exit_total 42
telemt_me_single_endpoint_outage_reconnect_attempt_total 42
telemt_me_single_endpoint_outage_reconnect_success_total 40
telemt_me_single_endpoint_quarantine_bypass_total 42
telemt_me_single_endpoint_shadow_rotate_total 1203
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
telemt_me_writers_active_current 46
telemt_desync_total 38655
telemt_desync_full_logged_total 12478
telemt_desync_suppressed_total 26177
telemt_desync_frames_bucket_total{bucket="1_2"} 9620
telemt_desync_frames_bucket_total{bucket="3_10"} 14392
telemt_desync_frames_bucket_total{bucket="gt_10"} 14643
telemt_pool_swap_total 170
telemt_pool_force_close_total 4752
telemt_pool_stale_pick_total 360
telemt_me_writer_close_signal_drop_total 613
telemt_me_draining_writers_reap_progress_total 53853
telemt_me_writer_removed_unexpected_total 1983
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5583
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 50323
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4313
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 439
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 49101
telemt_me_writer_teardown_success_total{mode="normal"} 55906
telemt_me_writer_teardown_noop_total 53858
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 107212
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 108883
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 109397
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 109714
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 109764
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 109764
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 109764
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 109764
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 109764
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 109764
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 109764
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 109764
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 109764
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 16.705610
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 109764
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 613
telemt_me_refill_failed_total 358
telemt_me_writer_restored_same_endpoint_total 1701
telemt_me_writer_restored_fallback_total 101
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 128
telemt_me_writer_removed_unexpected_minus_restored_total 181
telemt_user_connections_total{user="hello"} 8479319
telemt_user_connections_current{user="hello"} 1424
telemt_user_octets_from_client{user="hello"} 149125119305 (138.88 GB)
telemt_user_octets_to_client{user="hello"} 3246092421447 (2.95 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 574
telemt_user_unique_ips_recent_window{user="hello"} 292
```