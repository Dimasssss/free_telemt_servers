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

# Server Metrics 2026-03-22 14:32:03 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 62739.7 (17h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2025188
telemt_connections_bad_total 88173
telemt_connections_current 1751
telemt_connections_me_current 1751
telemt_handshake_timeouts_total 82624
telemt_upstream_connect_attempt_total 23387
telemt_upstream_connect_success_total 23386
telemt_upstream_connect_attempts_per_request{bucket="1"} 23386
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8106
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15213
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 54
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 949
telemt_me_reconnect_success_total 384
telemt_me_reader_eof_total 389
telemt_me_idle_close_by_peer_total 389
telemt_me_route_drop_no_conn_total 1471255
telemt_me_route_drop_channel_closed_total 662
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1726250
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_endpoint_quarantine_total 426
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 493
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
telemt_me_writers_active_current 43
telemt_desync_total 9225
telemt_desync_full_logged_total 2845
telemt_desync_suppressed_total 6380
telemt_desync_frames_bucket_total{bucket="1_2"} 2538
telemt_desync_frames_bucket_total{bucket="3_10"} 3454
telemt_desync_frames_bucket_total{bucket="gt_10"} 3233
telemt_pool_swap_total 69
telemt_pool_force_close_total 2109
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 358
telemt_me_draining_writers_reap_progress_total 21348
telemt_me_writer_removed_unexpected_total 379
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1525
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20022
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2068
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 41
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19239
telemt_me_writer_teardown_success_total{mode="normal"} 21547
telemt_me_writer_teardown_noop_total 21352
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 35919
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 37292
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 38560
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 40641
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 42058
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 42723
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 42896
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 42899
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 42899
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 42899
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 42899
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 42899
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 42899
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 169.637833
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 42899
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 358
telemt_me_refill_failed_total 30
telemt_me_writer_restored_same_endpoint_total 341
telemt_me_writer_removed_unexpected_minus_restored_total 38
telemt_user_connections_total{user="hello"} 1723246
telemt_user_connections_current{user="hello"} 1751
telemt_user_octets_from_client{user="hello"} 26872904200 (25.03 GB)
telemt_user_octets_to_client{user="hello"} 497860147104 (463.67 GB)
telemt_user_unique_ips_current{user="hello"} 649
telemt_user_unique_ips_recent_window{user="hello"} 276
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 76106.4 (21h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3270961
telemt_connections_bad_total 297818
telemt_connections_current 1687
telemt_connections_me_current 1687
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 77799
telemt_upstream_connect_attempt_total 48743
telemt_upstream_connect_success_total 48157
telemt_upstream_connect_fail_total 519
telemt_upstream_connect_attempts_per_request{bucket="1"} 48676
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28569
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19443
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 145
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 519
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 5577
telemt_me_reconnect_success_total 1887
telemt_me_reader_eof_total 1813
telemt_me_idle_close_by_peer_total 1813
telemt_me_route_drop_no_conn_total 3095987
telemt_me_route_drop_channel_closed_total 33
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2584916
telemt_me_endpoint_quarantine_total 625
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 36
telemt_me_single_endpoint_outage_exit_total 36
telemt_me_single_endpoint_outage_reconnect_attempt_total 36
telemt_me_single_endpoint_outage_reconnect_success_total 36
telemt_me_single_endpoint_quarantine_bypass_total 36
telemt_me_single_endpoint_shadow_rotate_total 592
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
telemt_desync_total 10137
telemt_desync_full_logged_total 5649
telemt_desync_suppressed_total 4488
telemt_desync_frames_bucket_total{bucket="1_2"} 2393
telemt_desync_frames_bucket_total{bucket="3_10"} 3994
telemt_desync_frames_bucket_total{bucket="gt_10"} 3750
telemt_pool_swap_total 73
telemt_pool_force_close_total 2144
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 180
telemt_me_draining_writers_reap_progress_total 30244
telemt_me_writer_removed_unexpected_total 1771
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3514
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 28502
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1852
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 292
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 28100
telemt_me_writer_teardown_success_total{mode="normal"} 32016
telemt_me_writer_teardown_noop_total 30244
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 60771
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 61721
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 61967
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 62227
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 62257
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 62260
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 62260
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 62260
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 62260
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 62260
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 62260
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 62260
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 62260
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.080009
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 62260
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 180
telemt_me_refill_failed_total 144
telemt_me_writer_restored_same_endpoint_total 1601
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 35
telemt_me_writer_removed_unexpected_minus_restored_total 146
telemt_user_connections_total{user="hello"} 2596360
telemt_user_connections_current{user="hello"} 1687
telemt_user_octets_from_client{user="hello"} 31105643347 (28.97 GB)
telemt_user_octets_to_client{user="hello"} 589544754846 (549.06 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 1079
telemt_user_unique_ips_recent_window{user="hello"} 982
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 150966.2 (41h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14463584
telemt_connections_bad_total 1277774
telemt_connections_current 5889
telemt_connections_me_current 5889
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 360177
telemt_upstream_connect_attempt_total 68940
telemt_upstream_connect_success_total 68849
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 68866
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34860
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32333
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1649
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2523
telemt_me_reconnect_success_total 1307
telemt_me_reader_eof_total 1246
telemt_me_idle_close_by_peer_total 1245
telemt_me_route_drop_no_conn_total 12797948
telemt_me_route_drop_channel_closed_total 130
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 11591919
telemt_me_endpoint_quarantine_total 959
telemt_me_single_endpoint_outage_enter_total 10
telemt_me_single_endpoint_outage_exit_total 10
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 1122
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
telemt_desync_total 47120
telemt_desync_full_logged_total 14864
telemt_desync_suppressed_total 32256
telemt_desync_frames_bucket_total{bucket="1_2"} 10665
telemt_desync_frames_bucket_total{bucket="3_10"} 18430
telemt_desync_frames_bucket_total{bucket="gt_10"} 18025
telemt_pool_swap_total 162
telemt_pool_force_close_total 5511
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 897
telemt_me_draining_writers_reap_progress_total 49782
telemt_me_writer_removed_unexpected_total 1201
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4329
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 45974
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 41
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5067
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 444
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 44271
telemt_me_writer_teardown_success_total{mode="normal"} 50303
telemt_me_writer_teardown_noop_total 49831
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 90536
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 93639
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 95128
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 97184
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 98676
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 99581
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 100095
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 100125
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 100126
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 100130
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 100132
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 100134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 100134
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 284.430550
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 100134
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 897
telemt_me_refill_failed_total 67
telemt_me_writer_restored_same_endpoint_total 1121
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 73
telemt_user_connections_total{user="hello"} 11593728
telemt_user_connections_current{user="hello"} 5889
telemt_user_octets_from_client{user="hello"} 164295640977 (153.01 GB)
telemt_user_octets_to_client{user="hello"} 3042008607791 (2.77 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 2211
telemt_user_unique_ips_recent_window{user="hello"} 1037
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 150967.3 (41h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10622301
telemt_connections_bad_total 1016060
telemt_connections_current 4482
telemt_connections_me_current 4482
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 315650
telemt_upstream_connect_attempt_total 80964
telemt_upstream_connect_success_total 79819
telemt_upstream_connect_fail_total 822
telemt_upstream_connect_attempts_per_request{bucket="1"} 80641
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43858
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32121
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 157
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3683
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 822
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 182
telemt_me_reconnect_attempts_total 3710
telemt_me_reconnect_success_total 1481
telemt_me_reader_eof_total 1356
telemt_me_idle_close_by_peer_total 1356
telemt_me_route_drop_no_conn_total 4218302
telemt_me_route_drop_channel_closed_total 460
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7932670
telemt_me_endpoint_quarantine_total 944
telemt_me_single_endpoint_outage_enter_total 24
telemt_me_single_endpoint_outage_exit_total 24
telemt_me_single_endpoint_outage_reconnect_attempt_total 29
telemt_me_single_endpoint_outage_reconnect_success_total 22
telemt_me_single_endpoint_quarantine_bypass_total 29
telemt_me_single_endpoint_shadow_rotate_total 1144
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
telemt_desync_total 35317
telemt_desync_full_logged_total 11885
telemt_desync_suppressed_total 23432
telemt_desync_frames_bucket_total{bucket="1_2"} 8698
telemt_desync_frames_bucket_total{bucket="3_10"} 13596
telemt_desync_frames_bucket_total{bucket="gt_10"} 13023
telemt_pool_swap_total 161
telemt_pool_force_close_total 4976
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 624
telemt_me_draining_writers_reap_progress_total 47985
telemt_me_writer_removed_unexpected_total 1388
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4368
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 44862
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 15
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4545
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 431
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 43009
telemt_me_writer_teardown_success_total{mode="normal"} 49230
telemt_me_writer_teardown_noop_total 48000
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 91287
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 94052
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 95075
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 96140
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 96837
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 97151
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 97220
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 97222
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 97228
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 97230
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 97230
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 97230
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 97230
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 95.273778
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 97230
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 624
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 1257
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 117
telemt_user_connections_total{user="hello"} 7871853
telemt_user_connections_current{user="hello"} 4482
telemt_user_octets_from_client{user="hello"} 198562175721 (184.93 GB)
telemt_user_octets_to_client{user="hello"} 3546358657502 (3.23 TB)
telemt_user_msgs_from_client{user="hello"} 113340
telemt_user_msgs_to_client{user="hello"} 116189
telemt_user_unique_ips_current{user="hello"} 1847
telemt_user_unique_ips_recent_window{user="hello"} 683
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 150932.1 (41h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10068753
telemt_connections_bad_total 856195
telemt_connections_current 4701
telemt_connections_me_current 4701
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 324062
telemt_upstream_connect_attempt_total 66396
telemt_upstream_connect_success_total 65482
telemt_upstream_connect_fail_total 182
telemt_upstream_connect_attempts_per_request{bucket="1"} 65664
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31441
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30821
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1195
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2025
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 182
telemt_me_keepalive_timeout_total 1383
telemt_me_reconnect_attempts_total 4535
telemt_me_reconnect_success_total 1843
telemt_me_reader_eof_total 1596
telemt_me_idle_close_by_peer_total 1595
telemt_me_route_drop_no_conn_total 4948386
telemt_me_route_drop_channel_closed_total 340
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7603526
telemt_me_endpoint_quarantine_total 1040
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 30
telemt_me_single_endpoint_outage_reconnect_success_total 24
telemt_me_single_endpoint_quarantine_bypass_total 30
telemt_me_single_endpoint_shadow_rotate_total 1108
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 55
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
telemt_desync_total 35105
telemt_desync_full_logged_total 11634
telemt_desync_suppressed_total 23471
telemt_desync_frames_bucket_total{bucket="1_2"} 8890
telemt_desync_frames_bucket_total{bucket="3_10"} 13429
telemt_desync_frames_bucket_total{bucket="gt_10"} 12786
telemt_pool_swap_total 157
telemt_pool_force_close_total 4928
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 665
telemt_me_draining_writers_reap_progress_total 48596
telemt_me_writer_removed_unexpected_total 1740
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4872
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 45373
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 24
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4399
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 529
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 43668
telemt_me_writer_teardown_success_total{mode="normal"} 50245
telemt_me_writer_teardown_noop_total 48666
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 93731
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 96120
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 96972
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 97932
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 98461
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 98653
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 98775
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 98803
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 98811
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 98824
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 98857
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 98860
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 98911
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3165.439978
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 98911
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 665
telemt_me_refill_failed_total 142
telemt_me_writer_restored_same_endpoint_total 1600
telemt_me_writer_restored_fallback_total 8
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 132
telemt_user_connections_total{user="hello"} 7597031
telemt_user_connections_current{user="hello"} 4701
telemt_user_octets_from_client{user="hello"} 177379525605 (165.20 GB)
telemt_user_octets_to_client{user="hello"} 3165326824681 (2.88 TB)
telemt_user_msgs_from_client{user="hello"} 46485
telemt_user_msgs_to_client{user="hello"} 113805
telemt_user_unique_ips_current{user="hello"} 1928
telemt_user_unique_ips_recent_window{user="hello"} 729
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 21211.8 (5h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8972888
telemt_connections_bad_total 564872
telemt_connections_current 7424
telemt_connections_me_current 7424
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 143862
telemt_upstream_connect_attempt_total 29159
telemt_upstream_connect_success_total 27718
telemt_upstream_connect_fail_total 1033
telemt_upstream_connect_attempts_per_request{bucket="1"} 28751
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15420
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7005
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 543
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4750
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1033
telemt_me_keepalive_timeout_total 846
telemt_me_reconnect_attempts_total 5521
telemt_me_reconnect_success_total 598
telemt_me_reader_eof_total 393
telemt_me_idle_close_by_peer_total 393
telemt_me_route_drop_no_conn_total 22080697
telemt_me_route_drop_channel_closed_total 34
telemt_me_route_drop_queue_full_total 26
telemt_me_route_drop_queue_full_profile_total{profile="high"} 26
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7465098
telemt_me_endpoint_quarantine_total 133
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 63
telemt_me_single_endpoint_outage_reconnect_success_total 21
telemt_me_single_endpoint_quarantine_bypass_total 63
telemt_me_single_endpoint_shadow_rotate_total 164
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
telemt_me_writers_active_current 44
telemt_desync_total 11100
telemt_desync_full_logged_total 2852
telemt_desync_suppressed_total 8248
telemt_desync_frames_bucket_total{bucket="1_2"} 1943
telemt_desync_frames_bucket_total{bucket="3_10"} 4468
telemt_desync_frames_bucket_total{bucket="gt_10"} 4689
telemt_pool_swap_total 19
telemt_pool_force_close_total 821
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 293
telemt_me_draining_writers_reap_progress_total 5653
telemt_me_writer_removed_unexpected_total 512
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 989
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 5139
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 560
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 261
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 4832
telemt_me_writer_teardown_success_total{mode="normal"} 6128
telemt_me_writer_teardown_noop_total 5657
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 9515
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 10622
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 11034
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 11484
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 11703
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 11779
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 11785
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 11785
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 11785
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 11785
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 11785
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 11785
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 11785
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 27.014047
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 11785
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 293
telemt_me_refill_failed_total 284
telemt_me_writer_restored_same_endpoint_total 428
telemt_me_writer_restored_fallback_total 3
telemt_me_no_writer_failfast_total 86
telemt_me_async_recovery_trigger_total 3059
telemt_me_writer_removed_unexpected_minus_restored_total 81
telemt_user_connections_total{user="hello"} 7479827
telemt_user_connections_current{user="hello"} 7424
telemt_user_octets_from_client{user="hello"} 43051467083 (40.09 GB)
telemt_user_octets_to_client{user="hello"} 218947628372 (203.91 GB)
telemt_user_msgs_from_client{user="hello"} 37295
telemt_user_msgs_to_client{user="hello"} 32778
telemt_user_unique_ips_current{user="hello"} 2655
telemt_user_unique_ips_recent_window{user="hello"} 1466
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 150938.2 (41h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9807987
telemt_connections_bad_total 816999
telemt_connections_current 5419
telemt_connections_me_current 5419
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 213701
telemt_upstream_connect_attempt_total 90906
telemt_upstream_connect_success_total 89988
telemt_upstream_connect_fail_total 796
telemt_upstream_connect_attempts_per_request{bucket="1"} 90784
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 55618
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32906
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 208
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1256
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 796
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 71448
telemt_me_reconnect_success_total 2478
telemt_me_reader_eof_total 2209
telemt_me_idle_close_by_peer_total 2208
telemt_me_route_drop_no_conn_total 4840455
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7738710
telemt_me_endpoint_quarantine_total 1014
telemt_me_single_endpoint_outage_enter_total 34
telemt_me_single_endpoint_outage_exit_total 34
telemt_me_single_endpoint_outage_reconnect_attempt_total 36
telemt_me_single_endpoint_outage_reconnect_success_total 34
telemt_me_single_endpoint_quarantine_bypass_total 36
telemt_me_single_endpoint_shadow_rotate_total 1124
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 47
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
telemt_desync_total 39804
telemt_desync_full_logged_total 13628
telemt_desync_suppressed_total 26176
telemt_desync_frames_bucket_total{bucket="1_2"} 8098
telemt_desync_frames_bucket_total{bucket="3_10"} 15447
telemt_desync_frames_bucket_total{bucket="gt_10"} 16259
telemt_pool_swap_total 154
telemt_pool_force_close_total 4592
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 560
telemt_me_draining_writers_reap_progress_total 51407
telemt_me_writer_removed_unexpected_total 2235
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5443
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 48217
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3942
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 650
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 46815
telemt_me_writer_teardown_success_total{mode="normal"} 53660
telemt_me_writer_teardown_noop_total 51408
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 103196
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 104386
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 104757
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 105024
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 105058
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 105061
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 105061
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 105064
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 105068
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 105068
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 105068
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 105068
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 105068
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 15.972372
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 105068
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 560
telemt_me_refill_failed_total 4255
telemt_me_writer_restored_same_endpoint_total 2083
telemt_me_writer_restored_fallback_total 42
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7358
telemt_me_writer_removed_unexpected_minus_restored_total 110
telemt_user_connections_total{user="hello"} 7739521
telemt_user_connections_current{user="hello"} 5419
telemt_user_octets_from_client{user="hello"} 177130724183 (164.97 GB)
telemt_user_octets_to_client{user="hello"} 2922179398517 (2.66 TB)
telemt_user_msgs_from_client{user="hello"} 146235
telemt_user_msgs_to_client{user="hello"} 572261
telemt_user_unique_ips_current{user="hello"} 2076
telemt_user_unique_ips_recent_window{user="hello"} 769
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 87774.2 (24h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9991182
telemt_connections_bad_total 363737
telemt_connections_current 4533
telemt_connections_me_current 4533
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4207789
telemt_upstream_connect_attempt_total 42964
telemt_upstream_connect_success_total 42654
telemt_upstream_connect_fail_total 303
telemt_upstream_connect_attempts_per_request{bucket="1"} 42957
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24308
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18227
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 119
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 303
telemt_me_reconnect_attempts_total 47938
telemt_me_reconnect_success_total 1451
telemt_me_reader_eof_total 1121
telemt_me_idle_close_by_peer_total 1121
telemt_me_route_drop_no_conn_total 3733311
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4806865
telemt_me_endpoint_quarantine_total 575
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 58
telemt_me_single_endpoint_outage_reconnect_success_total 18
telemt_me_single_endpoint_quarantine_bypass_total 58
telemt_me_single_endpoint_shadow_rotate_total 661
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
telemt_desync_total 26220
telemt_desync_full_logged_total 8842
telemt_desync_suppressed_total 17378
telemt_desync_frames_bucket_total{bucket="1_2"} 5309
telemt_desync_frames_bucket_total{bucket="3_10"} 10381
telemt_desync_frames_bucket_total{bucket="gt_10"} 10530
telemt_pool_swap_total 92
telemt_pool_force_close_total 2860
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 295
telemt_me_draining_writers_reap_progress_total 30272
telemt_me_writer_removed_unexpected_total 1186
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2737
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 28749
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2448
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 412
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 27412
telemt_me_writer_teardown_success_total{mode="normal"} 31486
telemt_me_writer_teardown_noop_total 30279
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 60725
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 61313
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 61552
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 61765
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 61765
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 61765
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 61765
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 61765
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 61765
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 61765
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 61765
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 61765
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 61765
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.290646
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 61765
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 295
telemt_me_refill_failed_total 2702
telemt_me_writer_restored_same_endpoint_total 1298
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4328
telemt_user_connections_total{user="hello"} 4801029
telemt_user_connections_current{user="hello"} 4533
telemt_user_octets_from_client{user="hello"} 104286893864 (97.12 GB)
telemt_user_octets_to_client{user="hello"} 1812287907518 (1.65 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 1827
telemt_user_unique_ips_recent_window{user="hello"} 729
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 68745.1 (19h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 843473
telemt_connections_bad_total 10755
telemt_connections_current 911
telemt_connections_me_current 911
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 16040
telemt_upstream_connect_attempt_total 34580
telemt_upstream_connect_success_total 34494
telemt_upstream_connect_fail_total 70
telemt_upstream_connect_attempts_per_request{bucket="1"} 34564
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15762
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18271
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 461
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 70
telemt_me_reconnect_attempts_total 1565
telemt_me_reconnect_success_total 668
telemt_me_reader_eof_total 643
telemt_me_idle_close_by_peer_total 643
telemt_me_route_drop_no_conn_total 290007
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 751952
telemt_me_endpoint_quarantine_total 616
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 573
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
telemt_me_writers_active_current 43
telemt_desync_total 4174
telemt_desync_full_logged_total 1257
telemt_desync_suppressed_total 2917
telemt_desync_frames_bucket_total{bucket="1_2"} 1000
telemt_desync_frames_bucket_total{bucket="3_10"} 1656
telemt_desync_frames_bucket_total{bucket="gt_10"} 1518
telemt_pool_swap_total 73
telemt_pool_force_close_total 1825
telemt_me_writer_close_signal_drop_total 106
telemt_me_draining_writers_reap_progress_total 28450
telemt_me_writer_removed_unexpected_total 622
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2191
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26904
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1747
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 78
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26625
telemt_me_writer_teardown_success_total{mode="normal"} 29095
telemt_me_writer_teardown_noop_total 28452
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 56956
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 57403
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 57522
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 57547
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 57547
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 57547
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 57547
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 57547
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 57547
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 57547
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 57547
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 57547
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 57547
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.180039
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 57547
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 106
telemt_me_refill_failed_total 49
telemt_me_writer_restored_same_endpoint_total 571
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 40
telemt_user_connections_total{user="hello"} 753136
telemt_user_connections_current{user="hello"} 911
telemt_user_octets_from_client{user="hello"} 13932876669 (12.98 GB)
telemt_user_octets_to_client{user="hello"} 351015860295 (326.91 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 373
telemt_user_unique_ips_recent_window{user="hello"} 124
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 150942.6 (41h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11977931
telemt_connections_bad_total 1398730
telemt_connections_current 6404
telemt_connections_me_current 6404
telemt_handshake_timeouts_total 327368
telemt_upstream_connect_attempt_total 56677
telemt_upstream_connect_success_total 56454
telemt_upstream_connect_fail_total 173
telemt_upstream_connect_attempts_per_request{bucket="1"} 56627
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27824
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28574
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 55
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 173
telemt_me_reconnect_attempts_total 2210
telemt_me_reconnect_success_total 1186
telemt_me_reader_eof_total 1148
telemt_me_idle_close_by_peer_total 1148
telemt_me_route_drop_no_conn_total 3880314
telemt_me_route_drop_channel_closed_total 116
telemt_me_route_drop_queue_full_total 36
telemt_me_route_drop_queue_full_profile_total{profile="high"} 36
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9023657
telemt_me_endpoint_quarantine_total 1029
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 12
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 12
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
telemt_desync_total 37065
telemt_desync_full_logged_total 12125
telemt_desync_suppressed_total 24940
telemt_desync_frames_bucket_total{bucket="1_2"} 8838
telemt_desync_frames_bucket_total{bucket="3_10"} 13737
telemt_desync_frames_bucket_total{bucket="gt_10"} 14490
telemt_pool_swap_total 167
telemt_pool_force_close_total 4614
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 587
telemt_me_draining_writers_reap_progress_total 51050
telemt_me_writer_removed_unexpected_total 1104
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4195
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 47989
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4449
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 165
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 46436
telemt_me_writer_teardown_success_total{mode="normal"} 52184
telemt_me_writer_teardown_noop_total 51052
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 100987
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 102485
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 102806
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 103103
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 103223
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 103236
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 103236
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 103236
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 103236
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 103236
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 103236
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 103236
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 103236
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.316935
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 103236
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 587
telemt_me_refill_failed_total 53
telemt_me_writer_restored_same_endpoint_total 1040
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 8993534
telemt_user_connections_current{user="hello"} 6404
telemt_user_octets_from_client{user="hello"} 173083688688 (161.20 GB)
telemt_user_octets_to_client{user="hello"} 4014825975140 (3.65 TB)
telemt_user_unique_ips_current{user="hello"} 2350
telemt_user_unique_ips_recent_window{user="hello"} 1013
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 150939.3 (41h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10345501
telemt_connections_bad_total 1158252
telemt_connections_current 5221
telemt_connections_me_current 5221
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 269190
telemt_upstream_connect_attempt_total 82217
telemt_upstream_connect_success_total 81607
telemt_upstream_connect_fail_total 528
telemt_upstream_connect_attempts_per_request{bucket="1"} 82135
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 45078
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33612
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 909
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2008
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 528
telemt_me_reconnect_attempts_total 8713
telemt_me_reconnect_success_total 1968
telemt_me_reader_eof_total 1831
telemt_me_idle_close_by_peer_total 1831
telemt_me_seq_mismatch_total 72
telemt_me_route_drop_no_conn_total 4846747
telemt_me_route_drop_channel_closed_total 329
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7977281
telemt_me_endpoint_quarantine_total 1149
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 38
telemt_me_single_endpoint_outage_exit_total 38
telemt_me_single_endpoint_outage_reconnect_attempt_total 38
telemt_me_single_endpoint_outage_reconnect_success_total 36
telemt_me_single_endpoint_quarantine_bypass_total 38
telemt_me_single_endpoint_shadow_rotate_total 1134
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 47
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
telemt_desync_total 36498
telemt_desync_full_logged_total 11842
telemt_desync_suppressed_total 24656
telemt_desync_frames_bucket_total{bucket="1_2"} 9036
telemt_desync_frames_bucket_total{bucket="3_10"} 13617
telemt_desync_frames_bucket_total{bucket="gt_10"} 13845
telemt_pool_swap_total 160
telemt_pool_force_close_total 4472
telemt_pool_stale_pick_total 360
telemt_me_writer_close_signal_drop_total 576
telemt_me_draining_writers_reap_progress_total 50337
telemt_me_writer_removed_unexpected_total 1856
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5222
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 47038
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4063
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 409
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 45865
telemt_me_writer_teardown_success_total{mode="normal"} 52260
telemt_me_writer_teardown_noop_total 50341
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 100199
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 101773
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 102263
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 102551
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 102601
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 102601
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 102601
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 102601
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 102601
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 102601
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 102601
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 102601
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 102601
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 15.709823
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 102601
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 576
telemt_me_refill_failed_total 346
telemt_me_writer_restored_same_endpoint_total 1592
telemt_me_writer_restored_fallback_total 98
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 128
telemt_me_writer_removed_unexpected_minus_restored_total 166
telemt_user_connections_total{user="hello"} 7983844
telemt_user_connections_current{user="hello"} 5221
telemt_user_octets_from_client{user="hello"} 140666179321 (131.01 GB)
telemt_user_octets_to_client{user="hello"} 3098211387907 (2.82 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 1983
telemt_user_unique_ips_recent_window{user="hello"} 806
```