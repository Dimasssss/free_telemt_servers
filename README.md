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

# Server Metrics 2026-03-22 18:01:27 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 75304.5 (20h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2729130
telemt_connections_bad_total 159104
telemt_connections_current 1671
telemt_connections_me_current 1671
telemt_handshake_timeouts_total 93184
telemt_upstream_connect_attempt_total 27696
telemt_upstream_connect_success_total 27695
telemt_upstream_connect_attempts_per_request{bucket="1"} 27695
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9602
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18004
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 65
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 150
telemt_me_reconnect_attempts_total 1127
telemt_me_reconnect_success_total 478
telemt_me_reader_eof_total 480
telemt_me_idle_close_by_peer_total 480
telemt_me_route_drop_no_conn_total 2228517
telemt_me_route_drop_channel_closed_total 935
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2320898
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
telemt_desync_total 10663
telemt_desync_full_logged_total 3376
telemt_desync_suppressed_total 7287
telemt_desync_frames_bucket_total{bucket="1_2"} 2851
telemt_desync_frames_bucket_total{bucket="3_10"} 3963
telemt_desync_frames_bucket_total{bucket="gt_10"} 3849
telemt_pool_swap_total 83
telemt_pool_force_close_total 2570
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 528
telemt_me_draining_writers_reap_progress_total 25285
telemt_me_writer_removed_unexpected_total 466
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1853
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 23667
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2518
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 52
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22715
telemt_me_writer_teardown_success_total{mode="normal"} 25520
telemt_me_writer_teardown_noop_total 25295
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 40695
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 42556
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 44357
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 47475
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 49568
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 50523
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 50811
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 50815
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 50815
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 50815
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 50815
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 50815
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 50815
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 251.576029
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 50815
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 528
telemt_me_refill_failed_total 34
telemt_me_writer_restored_same_endpoint_total 423
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 42
telemt_user_connections_total{user="hello"} 2317092
telemt_user_connections_current{user="hello"} 1671
telemt_user_octets_from_client{user="hello"} 34136468596 (31.79 GB)
telemt_user_octets_to_client{user="hello"} 614702468300 (572.49 GB)
telemt_user_unique_ips_current{user="hello"} 611
telemt_user_unique_ips_recent_window{user="hello"} 248
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 88670.3 (24h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3711690
telemt_connections_bad_total 335553
telemt_connections_current 765
telemt_connections_me_current 765
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 94597
telemt_upstream_connect_attempt_total 54487
telemt_upstream_connect_success_total 53814
telemt_upstream_connect_fail_total 593
telemt_upstream_connect_attempts_per_request{bucket="1"} 54407
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30868
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22772
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 174
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 593
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 6268
telemt_me_reconnect_success_total 2276
telemt_me_reader_eof_total 2208
telemt_me_idle_close_by_peer_total 2208
telemt_me_route_drop_no_conn_total 3567987
telemt_me_route_drop_channel_closed_total 36
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2945676
telemt_me_endpoint_quarantine_total 700
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 39
telemt_me_single_endpoint_outage_exit_total 39
telemt_me_single_endpoint_outage_reconnect_attempt_total 39
telemt_me_single_endpoint_outage_reconnect_success_total 38
telemt_me_single_endpoint_quarantine_bypass_total 39
telemt_me_single_endpoint_shadow_rotate_total 685
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
telemt_me_writers_active_current 47
telemt_desync_total 11604
telemt_desync_full_logged_total 6486
telemt_desync_suppressed_total 5118
telemt_desync_frames_bucket_total{bucket="1_2"} 2690
telemt_desync_frames_bucket_total{bucket="3_10"} 4548
telemt_desync_frames_bucket_total{bucket="gt_10"} 4366
telemt_pool_swap_total 84
telemt_pool_force_close_total 2522
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 212
telemt_me_draining_writers_reap_progress_total 35115
telemt_me_writer_removed_unexpected_total 2158
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4183
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 33101
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2160
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 362
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 32593
telemt_me_writer_teardown_success_total{mode="normal"} 37284
telemt_me_writer_teardown_noop_total 35115
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 70640
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 71746
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 72026
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 72333
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 72384
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 72397
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 72399
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 72399
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 72399
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 72399
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 72399
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 72399
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 72399
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 13.297683
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 72399
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 212
telemt_me_refill_failed_total 158
telemt_me_writer_restored_same_endpoint_total 1965
telemt_me_writer_restored_fallback_total 25
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 168
telemt_user_connections_total{user="hello"} 2956557
telemt_user_connections_current{user="hello"} 765
telemt_user_octets_from_client{user="hello"} 38066898135 (35.45 GB)
telemt_user_octets_to_client{user="hello"} 677999337830 (631.44 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 465
telemt_user_unique_ips_recent_window{user="hello"} 238
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 163530.4 (45h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15630339
telemt_connections_bad_total 1494330
telemt_connections_current 2328
telemt_connections_me_current 2328
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 384045
telemt_upstream_connect_attempt_total 73304
telemt_upstream_connect_success_total 73207
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 73224
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36651
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34868
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1681
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2745
telemt_me_reconnect_success_total 1399
telemt_me_reader_eof_total 1339
telemt_me_idle_close_by_peer_total 1337
telemt_me_route_drop_no_conn_total 13885229
telemt_me_route_drop_channel_closed_total 141
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12461667
telemt_me_endpoint_quarantine_total 1028
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1217
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
telemt_desync_total 51161
telemt_desync_full_logged_total 16059
telemt_desync_suppressed_total 35102
telemt_desync_frames_bucket_total{bucket="1_2"} 11427
telemt_desync_frames_bucket_total{bucket="3_10"} 19963
telemt_desync_frames_bucket_total{bucket="gt_10"} 19771
telemt_pool_swap_total 176
telemt_pool_force_close_total 5965
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 965
telemt_me_draining_writers_reap_progress_total 53707
telemt_me_writer_removed_unexpected_total 1293
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4696
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 49595
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 42
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5503
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 462
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 47742
telemt_me_writer_teardown_success_total{mode="normal"} 54291
telemt_me_writer_teardown_noop_total 53757
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 97688
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 101004
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 102646
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 104857
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 106445
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 107451
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 108009
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 108039
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 108040
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 108044
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 108046
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 108048
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 108048
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 305.459380
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 108048
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 965
telemt_me_refill_failed_total 74
telemt_me_writer_restored_same_endpoint_total 1204
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 82
telemt_user_connections_total{user="hello"} 12462567
telemt_user_connections_current{user="hello"} 2328
telemt_user_octets_from_client{user="hello"} 180197414793 (167.82 GB)
telemt_user_octets_to_client{user="hello"} 3254911900139 (2.96 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 890
telemt_user_unique_ips_recent_window{user="hello"} 345
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 163531.6 (45h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11276541
telemt_connections_bad_total 1106605
telemt_connections_current 1519
telemt_connections_me_current 1519
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 337777
telemt_upstream_connect_attempt_total 85742
telemt_upstream_connect_success_total 84542
telemt_upstream_connect_fail_total 838
telemt_upstream_connect_attempts_per_request{bucket="1"} 85380
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 45906
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34766
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 169
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3701
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 838
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 187
telemt_me_reconnect_attempts_total 4051
telemt_me_reconnect_success_total 1680
telemt_me_reader_eof_total 1549
telemt_me_idle_close_by_peer_total 1549
telemt_me_route_drop_no_conn_total 4423150
telemt_me_route_drop_channel_closed_total 489
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8400955
telemt_me_endpoint_quarantine_total 1034
telemt_me_single_endpoint_outage_enter_total 27
telemt_me_single_endpoint_outage_exit_total 27
telemt_me_single_endpoint_outage_reconnect_attempt_total 32
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 32
telemt_me_single_endpoint_shadow_rotate_total 1236
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
telemt_desync_total 37384
telemt_desync_full_logged_total 12574
telemt_desync_suppressed_total 24810
telemt_desync_frames_bucket_total{bucket="1_2"} 9193
telemt_desync_frames_bucket_total{bucket="3_10"} 14398
telemt_desync_frames_bucket_total{bucket="gt_10"} 13793
telemt_pool_swap_total 173
telemt_pool_force_close_total 5390
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 687
telemt_me_draining_writers_reap_progress_total 52135
telemt_me_writer_removed_unexpected_total 1588
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4835
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 48732
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4892
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 498
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 46745
telemt_me_writer_teardown_success_total{mode="normal"} 53567
telemt_me_writer_teardown_noop_total 52158
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 99280
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 102306
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 103407
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 104546
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 105301
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 105640
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 105715
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 105717
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 105723
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 105725
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 105725
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 105725
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 105725
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 102.424162
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 105725
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 687
telemt_me_refill_failed_total 128
telemt_me_writer_restored_same_endpoint_total 1440
telemt_me_writer_restored_fallback_total 15
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 133
telemt_user_connections_total{user="hello"} 8339434
telemt_user_connections_current{user="hello"} 1519
telemt_user_octets_from_client{user="hello"} 208137666513 (193.84 GB)
telemt_user_octets_to_client{user="hello"} 3759582256430 (3.42 TB)
telemt_user_msgs_from_client{user="hello"} 113340
telemt_user_msgs_to_client{user="hello"} 116189
telemt_user_unique_ips_current{user="hello"} 593
telemt_user_unique_ips_recent_window{user="hello"} 233
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 163496.0 (45h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10623787
telemt_connections_bad_total 915095
telemt_connections_current 1613
telemt_connections_me_current 1613
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 340498
telemt_upstream_connect_attempt_total 70883
telemt_upstream_connect_success_total 69884
telemt_upstream_connect_fail_total 182
telemt_upstream_connect_attempts_per_request{bucket="1"} 70066
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33062
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33300
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1419
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2103
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 182
telemt_me_keepalive_timeout_total 1383
telemt_me_reconnect_attempts_total 4799
telemt_me_reconnect_success_total 1945
telemt_me_reader_eof_total 1698
telemt_me_idle_close_by_peer_total 1697
telemt_me_route_drop_no_conn_total 5184751
telemt_me_route_drop_channel_closed_total 368
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8020088
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
telemt_desync_total 36864
telemt_desync_full_logged_total 12199
telemt_desync_suppressed_total 24665
telemt_desync_frames_bucket_total{bucket="1_2"} 9321
telemt_desync_frames_bucket_total{bucket="3_10"} 14103
telemt_desync_frames_bucket_total{bucket="gt_10"} 13440
telemt_pool_swap_total 171
telemt_pool_force_close_total 5320
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 691
telemt_me_draining_writers_reap_progress_total 52467
telemt_me_writer_removed_unexpected_total 1838
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5255
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 48965
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4777
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 543
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 47147
telemt_me_writer_teardown_success_total{mode="normal"} 54220
telemt_me_writer_teardown_noop_total 52538
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 101207
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 103744
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 104665
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 105708
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 106279
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 106491
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 106619
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 106650
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 106658
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 106671
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 106704
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 106707
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 106758
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3172.342699
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 106758
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 691
telemt_me_refill_failed_total 151
telemt_me_writer_restored_same_endpoint_total 1682
telemt_me_writer_restored_fallback_total 11
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 145
telemt_user_connections_total{user="hello"} 8012833
telemt_user_connections_current{user="hello"} 1613
telemt_user_octets_from_client{user="hello"} 184987098889 (172.28 GB)
telemt_user_octets_to_client{user="hello"} 3337052267069 (3.04 TB)
telemt_user_msgs_from_client{user="hello"} 46485
telemt_user_msgs_to_client{user="hello"} 113805
telemt_user_unique_ips_current{user="hello"} 578
telemt_user_unique_ips_recent_window{user="hello"} 234
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 33775.6 (9h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10471395
telemt_connections_bad_total 641716
telemt_connections_current 2566
telemt_connections_me_current 2566
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 208619
telemt_upstream_connect_attempt_total 41858
telemt_upstream_connect_success_total 39753
telemt_upstream_connect_fail_total 1483
telemt_upstream_connect_attempts_per_request{bucket="1"} 41236
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20433
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12013
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1389
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5918
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1483
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 6220
telemt_me_reconnect_success_total 798
telemt_me_reader_eof_total 502
telemt_me_idle_close_by_peer_total 502
telemt_me_route_drop_no_conn_total 25070575
telemt_me_route_drop_channel_closed_total 52
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8702498
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
telemt_desync_total 13845
telemt_desync_full_logged_total 3607
telemt_desync_suppressed_total 10238
telemt_desync_frames_bucket_total{bucket="1_2"} 2550
telemt_desync_frames_bucket_total{bucket="3_10"} 5621
telemt_desync_frames_bucket_total{bucket="gt_10"} 5674
telemt_pool_swap_total 33
telemt_pool_force_close_total 1246
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 391
telemt_me_draining_writers_reap_progress_total 9506
telemt_me_writer_removed_unexpected_total 704
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1472
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 8701
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 964
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 282
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 8260
telemt_me_writer_teardown_success_total{mode="normal"} 10173
telemt_me_writer_teardown_noop_total 9512
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 16707
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 18087
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 18573
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 19218
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 19528
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 19636
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 19685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 19685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 19685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 19685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 19685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 19685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 19685
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 43.193796
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 19685
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 391
telemt_me_refill_failed_total 300
telemt_me_writer_restored_same_endpoint_total 534
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 86
telemt_me_async_recovery_trigger_total 3059
telemt_me_writer_removed_unexpected_minus_restored_total 166
telemt_user_connections_total{user="hello"} 8724147
telemt_user_connections_current{user="hello"} 2566
telemt_user_octets_from_client{user="hello"} 74667568843 (69.54 GB)
telemt_user_octets_to_client{user="hello"} 386729808973 (360.17 GB)
telemt_user_msgs_from_client{user="hello"} 57283
telemt_user_msgs_to_client{user="hello"} 45481
telemt_user_unique_ips_current{user="hello"} 867
telemt_user_unique_ips_recent_window{user="hello"} 367
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 163502.3 (45h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10455810
telemt_connections_bad_total 880232
telemt_connections_current 1962
telemt_connections_me_current 1962
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 231934
telemt_upstream_connect_attempt_total 99597
telemt_upstream_connect_success_total 98566
telemt_upstream_connect_fail_total 876
telemt_upstream_connect_attempts_per_request{bucket="1"} 99442
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 60535
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36473
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1320
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 876
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 72148
telemt_me_reconnect_success_total 2687
telemt_me_reader_eof_total 2388
telemt_me_idle_close_by_peer_total 2386
telemt_me_route_drop_no_conn_total 5123687
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8250456
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
telemt_desync_total 43611
telemt_desync_full_logged_total 14870
telemt_desync_suppressed_total 28741
telemt_desync_frames_bucket_total{bucket="1_2"} 8866
telemt_desync_frames_bucket_total{bucket="3_10"} 16773
telemt_desync_frames_bucket_total{bucket="gt_10"} 17972
telemt_pool_swap_total 167
telemt_pool_force_close_total 4966
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 619
telemt_me_draining_writers_reap_progress_total 55562
telemt_me_writer_removed_unexpected_total 2429
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5936
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 52078
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4277
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 689
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 50596
telemt_me_writer_teardown_success_total{mode="normal"} 58014
telemt_me_writer_teardown_noop_total 55563
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 111528
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 112877
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 113261
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 113533
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 113567
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 113570
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 113570
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 113573
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 113577
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 113577
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 113577
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 113577
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 113577
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 16.671557
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 113577
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 619
telemt_me_refill_failed_total 4281
telemt_me_writer_restored_same_endpoint_total 2250
telemt_me_writer_restored_fallback_total 46
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7365
telemt_me_writer_removed_unexpected_minus_restored_total 133
telemt_user_connections_total{user="hello"} 8254097
telemt_user_connections_current{user="hello"} 1962
telemt_user_octets_from_client{user="hello"} 187203414329 (174.35 GB)
telemt_user_octets_to_client{user="hello"} 3119611813748 (2.84 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 743
telemt_user_unique_ips_recent_window{user="hello"} 258
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 100338.3 (27h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10939954
telemt_connections_bad_total 420558
telemt_connections_current 1659
telemt_connections_me_current 1659
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4545935
telemt_upstream_connect_attempt_total 47835
telemt_upstream_connect_success_total 47476
telemt_upstream_connect_fail_total 350
telemt_upstream_connect_attempts_per_request{bucket="1"} 47826
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26360
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20944
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 172
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 350
telemt_me_reconnect_attempts_total 48241
telemt_me_reconnect_success_total 1575
telemt_me_reader_eof_total 1233
telemt_me_idle_close_by_peer_total 1232
telemt_me_route_drop_no_conn_total 3973823
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5260717
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
telemt_desync_total 29335
telemt_desync_full_logged_total 9938
telemt_desync_suppressed_total 19397
telemt_desync_frames_bucket_total{bucket="1_2"} 5903
telemt_desync_frames_bucket_total{bucket="3_10"} 11571
telemt_desync_frames_bucket_total{bucket="gt_10"} 11861
telemt_pool_swap_total 106
telemt_pool_force_close_total 3248
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 336
telemt_me_draining_writers_reap_progress_total 34565
telemt_me_writer_removed_unexpected_total 1293
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3094
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 32797
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2826
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 422
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 31317
telemt_me_writer_teardown_success_total{mode="normal"} 35891
telemt_me_writer_teardown_noop_total 34572
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 69270
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 69964
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 70236
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 70463
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 70463
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 70463
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 70463
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 70463
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 70463
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 70463
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 70463
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 70463
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 70463
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.143223
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 70463
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 336
telemt_me_refill_failed_total 2712
telemt_me_writer_restored_same_endpoint_total 1399
telemt_me_writer_restored_fallback_total 16
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4330
telemt_user_connections_total{user="hello"} 5253890
telemt_user_connections_current{user="hello"} 1659
telemt_user_octets_from_client{user="hello"} 113429613464 (105.64 GB)
telemt_user_octets_to_client{user="hello"} 1997822897286 (1.82 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 605
telemt_user_unique_ips_recent_window{user="hello"} 259
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 81309.2 (22h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1159079
telemt_connections_bad_total 21107
telemt_connections_current 1286
telemt_connections_me_current 1286
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 22015
telemt_upstream_connect_attempt_total 39242
telemt_upstream_connect_success_total 39126
telemt_upstream_connect_fail_total 90
telemt_upstream_connect_attempts_per_request{bucket="1"} 39216
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17728
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20782
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 616
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 90
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 1754
telemt_me_reconnect_success_total 747
telemt_me_reader_eof_total 724
telemt_me_idle_close_by_peer_total 724
telemt_me_route_drop_no_conn_total 406000
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1029819
telemt_me_endpoint_quarantine_total 683
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 670
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
telemt_desync_total 5944
telemt_desync_full_logged_total 1821
telemt_desync_suppressed_total 4123
telemt_desync_frames_bucket_total{bucket="1_2"} 1389
telemt_desync_frames_bucket_total{bucket="3_10"} 2332
telemt_desync_frames_bucket_total{bucket="gt_10"} 2223
telemt_pool_swap_total 87
telemt_pool_force_close_total 2237
telemt_me_writer_close_signal_drop_total 127
telemt_me_draining_writers_reap_progress_total 32594
telemt_me_writer_removed_unexpected_total 697
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2526
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 30794
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2154
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 83
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 30357
telemt_me_writer_teardown_success_total{mode="normal"} 33320
telemt_me_writer_teardown_noop_total 32597
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 65220
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 65721
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 65885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 65917
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 65917
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 65917
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 65917
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 65917
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 65917
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 65917
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 65917
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 65917
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 65917
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.875977
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 65917
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 127
telemt_me_refill_failed_total 55
telemt_me_writer_restored_same_endpoint_total 637
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 1026161
telemt_user_connections_current{user="hello"} 1286
telemt_user_octets_from_client{user="hello"} 18826039309 (17.53 GB)
telemt_user_octets_to_client{user="hello"} 440329671567 (410.09 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 456
telemt_user_unique_ips_recent_window{user="hello"} 212
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 163506.8 (45h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12754260
telemt_connections_bad_total 1482351
telemt_connections_current 2212
telemt_connections_me_current 2212
telemt_handshake_timeouts_total 358141
telemt_upstream_connect_attempt_total 61556
telemt_upstream_connect_success_total 61255
telemt_upstream_connect_fail_total 190
telemt_upstream_connect_attempts_per_request{bucket="1"} 61445
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30214
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30953
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 86
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 190
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 2427
telemt_me_reconnect_success_total 1288
telemt_me_reader_eof_total 1250
telemt_me_idle_close_by_peer_total 1250
telemt_me_route_drop_no_conn_total 4331049
telemt_me_route_drop_channel_closed_total 121
telemt_me_route_drop_queue_full_total 37
telemt_me_route_drop_queue_full_profile_total{profile="high"} 37
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9649531
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
telemt_desync_total 39643
telemt_desync_full_logged_total 12930
telemt_desync_suppressed_total 26713
telemt_desync_frames_bucket_total{bucket="1_2"} 9445
telemt_desync_frames_bucket_total{bucket="3_10"} 14660
telemt_desync_frames_bucket_total{bucket="gt_10"} 15538
telemt_pool_swap_total 181
telemt_pool_force_close_total 4991
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 636
telemt_me_draining_writers_reap_progress_total 55370
telemt_me_writer_removed_unexpected_total 1203
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4564
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 52044
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4817
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 50379
telemt_me_writer_teardown_success_total{mode="normal"} 56608
telemt_me_writer_teardown_noop_total 55372
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 109520
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 111141
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 111502
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 111847
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 111967
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 111980
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 111980
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 111980
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 111980
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 111980
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 111980
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 111980
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 111980
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 18.804307
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 111980
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 636
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 1126
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 64
telemt_user_connections_total{user="hello"} 9617633
telemt_user_connections_current{user="hello"} 2212
telemt_user_octets_from_client{user="hello"} 188197936452 (175.27 GB)
telemt_user_octets_to_client{user="hello"} 4241040563024 (3.86 TB)
telemt_user_unique_ips_current{user="hello"} 718
telemt_user_unique_ips_recent_window{user="hello"} 280
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 163503.2 (45h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11062882
telemt_connections_bad_total 1241528
telemt_connections_current 1619
telemt_connections_me_current 1619
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 288675
telemt_upstream_connect_attempt_total 87643
telemt_upstream_connect_success_total 86884
telemt_upstream_connect_fail_total 582
telemt_upstream_connect_attempts_per_request{bucket="1"} 87466
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 47694
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36227
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 911
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2052
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 582
telemt_me_reconnect_attempts_total 9179
telemt_me_reconnect_success_total 2196
telemt_me_reader_eof_total 2046
telemt_me_idle_close_by_peer_total 2046
telemt_me_seq_mismatch_total 76
telemt_me_route_drop_no_conn_total 5511609
telemt_me_route_drop_channel_closed_total 351
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8555244
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
telemt_desync_total 38893
telemt_desync_full_logged_total 12562
telemt_desync_suppressed_total 26331
telemt_desync_frames_bucket_total{bucket="1_2"} 9686
telemt_desync_frames_bucket_total{bucket="3_10"} 14485
telemt_desync_frames_bucket_total{bucket="gt_10"} 14722
telemt_pool_swap_total 172
telemt_pool_force_close_total 4818
telemt_pool_stale_pick_total 360
telemt_me_writer_close_signal_drop_total 620
telemt_me_draining_writers_reap_progress_total 55027
telemt_me_writer_removed_unexpected_total 2072
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5756
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 51414
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4362
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 456
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 50209
telemt_me_writer_teardown_success_total{mode="normal"} 57170
telemt_me_writer_teardown_noop_total 55032
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 109625
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 111311
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 111833
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 112152
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 112202
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 112202
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 112202
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 112202
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 112202
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 112202
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 112202
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 112202
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 112202
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 16.868020
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 112202
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 620
telemt_me_refill_failed_total 358
telemt_me_writer_restored_same_endpoint_total 1784
telemt_me_writer_restored_fallback_total 104
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 128
telemt_me_writer_removed_unexpected_minus_restored_total 184
telemt_user_connections_total{user="hello"} 8561071
telemt_user_connections_current{user="hello"} 1619
telemt_user_octets_from_client{user="hello"} 150304161333 (139.98 GB)
telemt_user_octets_to_client{user="hello"} 3283420522635 (2.99 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 626
telemt_user_unique_ips_recent_window{user="hello"} 233
```