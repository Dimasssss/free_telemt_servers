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

# Server Metrics 2026-03-22 18:06:47 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 75610.0 (21h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2740780
telemt_connections_bad_total 160347
telemt_connections_current 1631
telemt_connections_me_current 1631
telemt_handshake_timeouts_total 93599
telemt_upstream_connect_attempt_total 27763
telemt_upstream_connect_success_total 27762
telemt_upstream_connect_attempts_per_request{bucket="1"} 27762
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9627
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18046
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 65
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 150
telemt_me_reconnect_attempts_total 1127
telemt_me_reconnect_success_total 478
telemt_me_reader_eof_total 480
telemt_me_idle_close_by_peer_total 480
telemt_me_route_drop_no_conn_total 2232261
telemt_me_route_drop_channel_closed_total 938
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2330426
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_endpoint_quarantine_total 512
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 588
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
telemt_me_writers_active_current 43
telemt_desync_total 10686
telemt_desync_full_logged_total 3386
telemt_desync_suppressed_total 7300
telemt_desync_frames_bucket_total{bucket="1_2"} 2861
telemt_desync_frames_bucket_total{bucket="3_10"} 3968
telemt_desync_frames_bucket_total{bucket="gt_10"} 3857
telemt_pool_swap_total 83
telemt_pool_force_close_total 2570
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 528
telemt_me_draining_writers_reap_progress_total 25352
telemt_me_writer_removed_unexpected_total 466
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1854
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 23733
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2518
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 52
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22782
telemt_me_writer_teardown_success_total{mode="normal"} 25587
telemt_me_writer_teardown_noop_total 25362
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 40821
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 42685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 44491
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 47609
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 49702
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 50657
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 50945
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 50949
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 50949
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 50949
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 50949
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 50949
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 50949
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 251.622574
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 50949
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 528
telemt_me_refill_failed_total 34
telemt_me_writer_restored_same_endpoint_total 423
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 42
telemt_user_connections_total{user="hello"} 2326596
telemt_user_connections_current{user="hello"} 1631
telemt_user_octets_from_client{user="hello"} 34313459668 (31.96 GB)
telemt_user_octets_to_client{user="hello"} 617904091248 (575.47 GB)
telemt_user_unique_ips_current{user="hello"} 602
telemt_user_unique_ips_recent_window{user="hello"} 237
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 88976.0 (24h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3717745
telemt_connections_bad_total 335696
telemt_connections_current 1140
telemt_connections_me_current 1140
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 94652
telemt_upstream_connect_attempt_total 54568
telemt_upstream_connect_success_total 53895
telemt_upstream_connect_fail_total 593
telemt_upstream_connect_attempts_per_request{bucket="1"} 54488
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30889
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22831
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 175
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 593
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 6268
telemt_me_reconnect_success_total 2276
telemt_me_reader_eof_total 2208
telemt_me_idle_close_by_peer_total 2208
telemt_me_route_drop_no_conn_total 3569609
telemt_me_route_drop_channel_closed_total 36
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2951157
telemt_me_endpoint_quarantine_total 700
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 39
telemt_me_single_endpoint_outage_exit_total 39
telemt_me_single_endpoint_outage_reconnect_attempt_total 39
telemt_me_single_endpoint_outage_reconnect_success_total 38
telemt_me_single_endpoint_quarantine_bypass_total 39
telemt_me_single_endpoint_shadow_rotate_total 686
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
telemt_desync_total 11630
telemt_desync_full_logged_total 6504
telemt_desync_suppressed_total 5126
telemt_desync_frames_bucket_total{bucket="1_2"} 2696
telemt_desync_frames_bucket_total{bucket="3_10"} 4559
telemt_desync_frames_bucket_total{bucket="gt_10"} 4375
telemt_pool_swap_total 84
telemt_pool_force_close_total 2522
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 212
telemt_me_draining_writers_reap_progress_total 35196
telemt_me_writer_removed_unexpected_total 2158
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4186
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 33179
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2160
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 362
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 32674
telemt_me_writer_teardown_success_total{mode="normal"} 37365
telemt_me_writer_teardown_noop_total 35196
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 70802
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 71908
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 72188
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 72495
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 72546
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 72559
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 72561
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 72561
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 72561
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 72561
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 72561
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 72561
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 72561
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 13.299362
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 72561
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 212
telemt_me_refill_failed_total 158
telemt_me_writer_restored_same_endpoint_total 1965
telemt_me_writer_restored_fallback_total 25
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 168
telemt_user_connections_total{user="hello"} 2962036
telemt_user_connections_current{user="hello"} 1140
telemt_user_octets_from_client{user="hello"} 38215915695 (35.59 GB)
telemt_user_octets_to_client{user="hello"} 680267877602 (633.55 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 641
telemt_user_unique_ips_recent_window{user="hello"} 244
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 163836.1 (45h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15647555
telemt_connections_bad_total 1497122
telemt_connections_current 2595
telemt_connections_me_current 2595
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 385109
telemt_upstream_connect_attempt_total 73383
telemt_upstream_connect_success_total 73286
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 73303
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36671
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34927
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1681
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2745
telemt_me_reconnect_success_total 1399
telemt_me_reader_eof_total 1339
telemt_me_idle_close_by_peer_total 1337
telemt_me_route_drop_no_conn_total 13890069
telemt_me_route_drop_channel_closed_total 141
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12474304
telemt_me_endpoint_quarantine_total 1028
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1219
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
telemt_me_writers_warm_current 11
telemt_desync_total 51219
telemt_desync_full_logged_total 16078
telemt_desync_suppressed_total 35141
telemt_desync_frames_bucket_total{bucket="1_2"} 11437
telemt_desync_frames_bucket_total{bucket="3_10"} 19975
telemt_desync_frames_bucket_total{bucket="gt_10"} 19807
telemt_pool_swap_total 176
telemt_pool_force_close_total 5965
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 965
telemt_me_draining_writers_reap_progress_total 53773
telemt_me_writer_removed_unexpected_total 1293
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4696
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 49661
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 42
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5503
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 462
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 47808
telemt_me_writer_teardown_success_total{mode="normal"} 54357
telemt_me_writer_teardown_noop_total 53823
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 97820
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 101136
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 102778
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 104989
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 106577
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 107583
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 108141
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 108171
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 108172
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 108176
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 108178
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 108180
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 108180
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 305.462367
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 108180
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 965
telemt_me_refill_failed_total 74
telemt_me_writer_restored_same_endpoint_total 1204
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 82
telemt_user_connections_total{user="hello"} 12475181
telemt_user_connections_current{user="hello"} 2595
telemt_user_octets_from_client{user="hello"} 180405358681 (168.02 GB)
telemt_user_octets_to_client{user="hello"} 3259741900851 (2.96 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 1004
telemt_user_unique_ips_recent_window{user="hello"} 281
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 163836.9 (45h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11290075
telemt_connections_bad_total 1110196
telemt_connections_current 1559
telemt_connections_me_current 1559
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 338151
telemt_upstream_connect_attempt_total 85846
telemt_upstream_connect_success_total 84646
telemt_upstream_connect_fail_total 838
telemt_upstream_connect_attempts_per_request{bucket="1"} 85484
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 45946
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34830
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 169
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3701
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 838
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 187
telemt_me_reconnect_attempts_total 4051
telemt_me_reconnect_success_total 1680
telemt_me_reader_eof_total 1549
telemt_me_idle_close_by_peer_total 1549
telemt_me_route_drop_no_conn_total 4426823
telemt_me_route_drop_channel_closed_total 490
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8409967
telemt_me_endpoint_quarantine_total 1034
telemt_me_single_endpoint_outage_enter_total 27
telemt_me_single_endpoint_outage_exit_total 27
telemt_me_single_endpoint_outage_reconnect_attempt_total 32
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 32
telemt_me_single_endpoint_shadow_rotate_total 1237
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
telemt_me_writers_warm_current 9
telemt_desync_total 37442
telemt_desync_full_logged_total 12590
telemt_desync_suppressed_total 24852
telemt_desync_frames_bucket_total{bucket="1_2"} 9212
telemt_desync_frames_bucket_total{bucket="3_10"} 14423
telemt_desync_frames_bucket_total{bucket="gt_10"} 13807
telemt_pool_swap_total 173
telemt_pool_force_close_total 5390
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 687
telemt_me_draining_writers_reap_progress_total 52230
telemt_me_writer_removed_unexpected_total 1588
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4835
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 48827
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4892
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 498
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 46840
telemt_me_writer_teardown_success_total{mode="normal"} 53662
telemt_me_writer_teardown_noop_total 52253
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 99470
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 102496
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 103597
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 104736
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 105491
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 105830
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 105905
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 105907
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 105913
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 105915
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 105915
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 105915
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 105915
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 102.425368
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 105915
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 687
telemt_me_refill_failed_total 128
telemt_me_writer_restored_same_endpoint_total 1440
telemt_me_writer_restored_fallback_total 15
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 133
telemt_user_connections_total{user="hello"} 8348444
telemt_user_connections_current{user="hello"} 1559
telemt_user_octets_from_client{user="hello"} 208407624445 (194.09 GB)
telemt_user_octets_to_client{user="hello"} 3764658554570 (3.42 TB)
telemt_user_msgs_from_client{user="hello"} 113340
telemt_user_msgs_to_client{user="hello"} 116189
telemt_user_unique_ips_current{user="hello"} 645
telemt_user_unique_ips_recent_window{user="hello"} 221
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 163801.8 (45h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10632985
telemt_connections_bad_total 915614
telemt_connections_current 1434
telemt_connections_me_current 1434
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 340887
telemt_upstream_connect_attempt_total 70970
telemt_upstream_connect_success_total 69968
telemt_upstream_connect_fail_total 182
telemt_upstream_connect_attempts_per_request{bucket="1"} 70150
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33086
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33349
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1429
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2104
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 182
telemt_me_keepalive_timeout_total 1383
telemt_me_reconnect_attempts_total 4802
telemt_me_reconnect_success_total 1948
telemt_me_reader_eof_total 1701
telemt_me_idle_close_by_peer_total 1700
telemt_me_route_drop_no_conn_total 5189073
telemt_me_route_drop_channel_closed_total 368
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8027925
telemt_me_endpoint_quarantine_total 1112
telemt_me_single_endpoint_outage_enter_total 32
telemt_me_single_endpoint_outage_exit_total 32
telemt_me_single_endpoint_outage_reconnect_attempt_total 33
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 33
telemt_me_single_endpoint_shadow_rotate_total 1205
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
telemt_me_writers_active_current 44
telemt_desync_total 36892
telemt_desync_full_logged_total 12209
telemt_desync_suppressed_total 24683
telemt_desync_frames_bucket_total{bucket="1_2"} 9331
telemt_desync_frames_bucket_total{bucket="3_10"} 14111
telemt_desync_frames_bucket_total{bucket="gt_10"} 13450
telemt_pool_swap_total 171
telemt_pool_force_close_total 5320
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 692
telemt_me_draining_writers_reap_progress_total 52524
telemt_me_writer_removed_unexpected_total 1841
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5258
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 49022
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4777
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 543
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 47204
telemt_me_writer_teardown_success_total{mode="normal"} 54280
telemt_me_writer_teardown_noop_total 52595
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 101323
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 103861
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 104782
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 105825
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 106396
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 106608
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 106736
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 106767
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 106775
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 106788
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 106821
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 106824
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 106875
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3172.345422
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 106875
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 692
telemt_me_refill_failed_total 151
telemt_me_writer_restored_same_endpoint_total 1685
telemt_me_writer_restored_fallback_total 11
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 145
telemt_user_connections_total{user="hello"} 8020670
telemt_user_connections_current{user="hello"} 1434
telemt_user_octets_from_client{user="hello"} 185136568705 (172.42 GB)
telemt_user_octets_to_client{user="hello"} 3340837455541 (3.04 TB)
telemt_user_msgs_from_client{user="hello"} 46485
telemt_user_msgs_to_client{user="hello"} 113805
telemt_user_unique_ips_current{user="hello"} 547
telemt_user_unique_ips_recent_window{user="hello"} 218
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 34096.4 (9h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10489277
telemt_connections_bad_total 642971
telemt_connections_current 2292
telemt_connections_me_current 2292
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 210174
telemt_upstream_connect_attempt_total 41937
telemt_upstream_connect_success_total 39831
telemt_upstream_connect_fail_total 1483
telemt_upstream_connect_attempts_per_request{bucket="1"} 41314
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20465
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12059
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1389
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5918
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1483
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 6222
telemt_me_reconnect_success_total 800
telemt_me_reader_eof_total 504
telemt_me_idle_close_by_peer_total 504
telemt_me_route_drop_no_conn_total 25079011
telemt_me_route_drop_channel_closed_total 52
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8716653
telemt_me_endpoint_quarantine_total 215
telemt_me_single_endpoint_outage_enter_total 60
telemt_me_single_endpoint_outage_exit_total 60
telemt_me_single_endpoint_outage_reconnect_attempt_total 111
telemt_me_single_endpoint_outage_reconnect_success_total 33
telemt_me_single_endpoint_quarantine_bypass_total 111
telemt_me_single_endpoint_shadow_rotate_total 267
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
telemt_me_writers_active_current 45
telemt_desync_total 13884
telemt_desync_full_logged_total 3615
telemt_desync_suppressed_total 10269
telemt_desync_frames_bucket_total{bucket="1_2"} 2558
telemt_desync_frames_bucket_total{bucket="3_10"} 5630
telemt_desync_frames_bucket_total{bucket="gt_10"} 5696
telemt_pool_swap_total 33
telemt_pool_force_close_total 1246
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 391
telemt_me_draining_writers_reap_progress_total 9561
telemt_me_writer_removed_unexpected_total 706
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1474
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 8756
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 964
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 282
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 8315
telemt_me_writer_teardown_success_total{mode="normal"} 10230
telemt_me_writer_teardown_noop_total 9567
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 16819
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 18199
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 18685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 19330
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 19640
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 19748
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 19797
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 19797
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 19797
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 19797
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 19797
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 19797
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 19797
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 43.195173
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 19797
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 391
telemt_me_refill_failed_total 300
telemt_me_writer_restored_same_endpoint_total 536
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 86
telemt_me_async_recovery_trigger_total 3059
telemt_me_writer_removed_unexpected_minus_restored_total 166
telemt_user_connections_total{user="hello"} 8738300
telemt_user_connections_current{user="hello"} 2292
telemt_user_octets_from_client{user="hello"} 74788439815 (69.65 GB)
telemt_user_octets_to_client{user="hello"} 392287956985 (365.35 GB)
telemt_user_msgs_from_client{user="hello"} 57283
telemt_user_msgs_to_client{user="hello"} 45481
telemt_user_unique_ips_current{user="hello"} 852
telemt_user_unique_ips_recent_window{user="hello"} 321
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 163807.7 (45h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10467640
telemt_connections_bad_total 881483
telemt_connections_current 2022
telemt_connections_me_current 2022
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 231998
telemt_upstream_connect_attempt_total 99705
telemt_upstream_connect_success_total 98673
telemt_upstream_connect_fail_total 876
telemt_upstream_connect_attempts_per_request{bucket="1"} 99549
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 60574
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36540
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1321
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 876
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 72151
telemt_me_reconnect_success_total 2690
telemt_me_reader_eof_total 2391
telemt_me_idle_close_by_peer_total 2389
telemt_me_route_drop_no_conn_total 5127365
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8260218
telemt_me_endpoint_quarantine_total 1092
telemt_me_single_endpoint_outage_enter_total 38
telemt_me_single_endpoint_outage_exit_total 38
telemt_me_single_endpoint_outage_reconnect_attempt_total 40
telemt_me_single_endpoint_outage_reconnect_success_total 38
telemt_me_single_endpoint_quarantine_bypass_total 40
telemt_me_single_endpoint_shadow_rotate_total 1219
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
telemt_me_writers_active_current 47
telemt_desync_total 43663
telemt_desync_full_logged_total 14889
telemt_desync_suppressed_total 28774
telemt_desync_frames_bucket_total{bucket="1_2"} 8873
telemt_desync_frames_bucket_total{bucket="3_10"} 16787
telemt_desync_frames_bucket_total{bucket="gt_10"} 18003
telemt_pool_swap_total 167
telemt_pool_force_close_total 4966
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 619
telemt_me_draining_writers_reap_progress_total 55646
telemt_me_writer_removed_unexpected_total 2432
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5942
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 52159
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4277
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 689
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 50680
telemt_me_writer_teardown_success_total{mode="normal"} 58101
telemt_me_writer_teardown_noop_total 55647
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 111699
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 113048
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 113432
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 113704
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 113738
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 113741
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 113741
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 113744
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 113748
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 113748
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 113748
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 113748
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 113748
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 16.672370
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 113748
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 619
telemt_me_refill_failed_total 4281
telemt_me_writer_restored_same_endpoint_total 2253
telemt_me_writer_restored_fallback_total 46
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7365
telemt_me_writer_removed_unexpected_minus_restored_total 133
telemt_user_connections_total{user="hello"} 8263862
telemt_user_connections_current{user="hello"} 2022
telemt_user_octets_from_client{user="hello"} 187364900913 (174.50 GB)
telemt_user_octets_to_client{user="hello"} 3123315290280 (2.84 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 795
telemt_user_unique_ips_recent_window{user="hello"} 257
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 100643.9 (27h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10955661
telemt_connections_bad_total 421937
telemt_connections_current 1567
telemt_connections_me_current 1567
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4549670
telemt_upstream_connect_attempt_total 47920
telemt_upstream_connect_success_total 47561
telemt_upstream_connect_fail_total 350
telemt_upstream_connect_attempts_per_request{bucket="1"} 47911
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26397
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20992
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 172
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 350
telemt_me_reconnect_attempts_total 48242
telemt_me_reconnect_success_total 1576
telemt_me_reader_eof_total 1233
telemt_me_idle_close_by_peer_total 1232
telemt_me_route_drop_no_conn_total 3977677
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5269195
telemt_me_endpoint_quarantine_total 649
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 58
telemt_me_single_endpoint_outage_reconnect_success_total 18
telemt_me_single_endpoint_quarantine_bypass_total 58
telemt_me_single_endpoint_shadow_rotate_total 757
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
telemt_me_writers_active_current 44
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 29392
telemt_desync_full_logged_total 9952
telemt_desync_suppressed_total 19440
telemt_desync_frames_bucket_total{bucket="1_2"} 5909
telemt_desync_frames_bucket_total{bucket="3_10"} 11595
telemt_desync_frames_bucket_total{bucket="gt_10"} 11888
telemt_pool_swap_total 106
telemt_pool_force_close_total 3248
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 337
telemt_me_draining_writers_reap_progress_total 34647
telemt_me_writer_removed_unexpected_total 1294
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3097
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 32877
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2826
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 422
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 31399
telemt_me_writer_teardown_success_total{mode="normal"} 35974
telemt_me_writer_teardown_noop_total 34654
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 69435
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 70129
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 70401
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 70628
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 70628
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 70628
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 70628
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 70628
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 70628
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 70628
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 70628
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 70628
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 70628
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.143871
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 70628
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 337
telemt_me_refill_failed_total 2712
telemt_me_writer_restored_same_endpoint_total 1400
telemt_me_writer_restored_fallback_total 16
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4330
telemt_user_connections_total{user="hello"} 5262368
telemt_user_connections_current{user="hello"} 1567
telemt_user_octets_from_client{user="hello"} 113520897472 (105.72 GB)
telemt_user_octets_to_client{user="hello"} 2001741106958 (1.82 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 559
telemt_user_unique_ips_recent_window{user="hello"} 236
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 81614.9 (22h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1168015
telemt_connections_bad_total 22313
telemt_connections_current 1248
telemt_connections_me_current 1248
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 22529
telemt_upstream_connect_attempt_total 39328
telemt_upstream_connect_success_total 39212
telemt_upstream_connect_fail_total 90
telemt_upstream_connect_attempts_per_request{bucket="1"} 39302
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17760
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20830
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 622
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 90
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 1757
telemt_me_reconnect_success_total 749
telemt_me_reader_eof_total 726
telemt_me_idle_close_by_peer_total 726
telemt_me_route_drop_no_conn_total 408684
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1036652
telemt_me_endpoint_quarantine_total 684
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 672
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
telemt_desync_total 5972
telemt_desync_full_logged_total 1831
telemt_desync_suppressed_total 4141
telemt_desync_frames_bucket_total{bucket="1_2"} 1392
telemt_desync_frames_bucket_total{bucket="3_10"} 2343
telemt_desync_frames_bucket_total{bucket="gt_10"} 2237
telemt_pool_swap_total 87
telemt_pool_force_close_total 2237
telemt_me_writer_close_signal_drop_total 127
telemt_me_draining_writers_reap_progress_total 32659
telemt_me_writer_removed_unexpected_total 699
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2532
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 30855
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2154
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 83
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 30422
telemt_me_writer_teardown_success_total{mode="normal"} 33387
telemt_me_writer_teardown_noop_total 32662
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 65352
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 65853
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 66017
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 66049
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 66049
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 66049
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 66049
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 66049
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 66049
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 66049
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 66049
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 66049
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 66049
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.878677
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 66049
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 127
telemt_me_refill_failed_total 55
telemt_me_writer_restored_same_endpoint_total 639
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 1032993
telemt_user_connections_current{user="hello"} 1248
telemt_user_octets_from_client{user="hello"} 18989938325 (17.69 GB)
telemt_user_octets_to_client{user="hello"} 443177135995 (412.74 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 425
telemt_user_unique_ips_recent_window{user="hello"} 162
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 163822.8 (45h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12766334
telemt_connections_bad_total 1483045
telemt_connections_current 2175
telemt_connections_me_current 2175
telemt_handshake_timeouts_total 358829
telemt_upstream_connect_attempt_total 61655
telemt_upstream_connect_success_total 61349
telemt_upstream_connect_fail_total 190
telemt_upstream_connect_attempts_per_request{bucket="1"} 61539
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30265
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30992
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 88
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 190
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 2427
telemt_me_reconnect_success_total 1288
telemt_me_reader_eof_total 1250
telemt_me_idle_close_by_peer_total 1250
telemt_me_route_drop_no_conn_total 4337325
telemt_me_route_drop_channel_closed_total 121
telemt_me_route_drop_queue_full_total 37
telemt_me_route_drop_queue_full_profile_total{profile="high"} 37
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9659637
telemt_me_endpoint_quarantine_total 1087
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1222
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
telemt_me_writers_active_current 47
telemt_desync_total 39691
telemt_desync_full_logged_total 12944
telemt_desync_suppressed_total 26747
telemt_desync_frames_bucket_total{bucket="1_2"} 9452
telemt_desync_frames_bucket_total{bucket="3_10"} 14675
telemt_desync_frames_bucket_total{bucket="gt_10"} 15564
telemt_pool_swap_total 181
telemt_pool_force_close_total 4991
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 636
telemt_me_draining_writers_reap_progress_total 55462
telemt_me_writer_removed_unexpected_total 1203
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4566
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 52134
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4817
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 50471
telemt_me_writer_teardown_success_total{mode="normal"} 56700
telemt_me_writer_teardown_noop_total 55464
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 109704
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 111325
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 111686
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 112031
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 112151
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 112164
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 112164
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 112164
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 112164
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 112164
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 112164
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 112164
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 112164
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 18.806345
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 112164
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 636
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 1126
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 64
telemt_user_connections_total{user="hello"} 9627737
telemt_user_connections_current{user="hello"} 2175
telemt_user_octets_from_client{user="hello"} 188443476252 (175.50 GB)
telemt_user_octets_to_client{user="hello"} 4246113361088 (3.86 TB)
telemt_user_unique_ips_current{user="hello"} 724
telemt_user_unique_ips_recent_window{user="hello"} 220
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 163808.9 (45h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11077606
telemt_connections_bad_total 1246073
telemt_connections_current 1572
telemt_connections_me_current 1572
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 289158
telemt_upstream_connect_attempt_total 87736
telemt_upstream_connect_success_total 86975
telemt_upstream_connect_fail_total 582
telemt_upstream_connect_attempts_per_request{bucket="1"} 87557
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 47730
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36282
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 911
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2052
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 582
telemt_me_reconnect_attempts_total 9181
telemt_me_reconnect_success_total 2198
telemt_me_reader_eof_total 2048
telemt_me_idle_close_by_peer_total 2048
telemt_me_seq_mismatch_total 76
telemt_me_route_drop_no_conn_total 5515637
telemt_me_route_drop_channel_closed_total 351
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8564472
telemt_me_endpoint_quarantine_total 1251
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 43
telemt_me_single_endpoint_outage_exit_total 43
telemt_me_single_endpoint_outage_reconnect_attempt_total 43
telemt_me_single_endpoint_outage_reconnect_success_total 41
telemt_me_single_endpoint_quarantine_bypass_total 43
telemt_me_single_endpoint_shadow_rotate_total 1224
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 52
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
telemt_desync_total 38928
telemt_desync_full_logged_total 12574
telemt_desync_suppressed_total 26354
telemt_desync_frames_bucket_total{bucket="1_2"} 9691
telemt_desync_frames_bucket_total{bucket="3_10"} 14493
telemt_desync_frames_bucket_total{bucket="gt_10"} 14744
telemt_pool_swap_total 172
telemt_pool_force_close_total 4818
telemt_pool_stale_pick_total 360
telemt_me_writer_close_signal_drop_total 620
telemt_me_draining_writers_reap_progress_total 55098
telemt_me_writer_removed_unexpected_total 2074
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5758
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 51485
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4362
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 456
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 50280
telemt_me_writer_teardown_success_total{mode="normal"} 57243
telemt_me_writer_teardown_noop_total 55103
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 109769
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 111455
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 111977
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 112296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 112346
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 112346
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 112346
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 112346
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 112346
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 112346
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 112346
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 112346
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 112346
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 16.869611
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 112346
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 620
telemt_me_refill_failed_total 358
telemt_me_writer_restored_same_endpoint_total 1786
telemt_me_writer_restored_fallback_total 104
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 128
telemt_me_writer_removed_unexpected_minus_restored_total 184
telemt_user_connections_total{user="hello"} 8570298
telemt_user_connections_current{user="hello"} 1572
telemt_user_octets_from_client{user="hello"} 150466401841 (140.13 GB)
telemt_user_octets_to_client{user="hello"} 3289209547211 (2.99 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 644
telemt_user_unique_ips_recent_window{user="hello"} 234
```