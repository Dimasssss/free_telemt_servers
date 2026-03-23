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

# Server Metrics 2026-03-23 01:56:44 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 103821.0 (28h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3578065
telemt_connections_bad_total 326995
telemt_connections_current 869
telemt_connections_me_current 869
telemt_handshake_timeouts_total 112538
telemt_upstream_connect_attempt_total 38719
telemt_upstream_connect_success_total 38718
telemt_upstream_connect_attempts_per_request{bucket="1"} 38718
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13457
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25127
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 92
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 451
telemt_me_reconnect_attempts_total 1410
telemt_me_reconnect_success_total 613
telemt_me_reader_eof_total 630
telemt_me_idle_close_by_peer_total 630
telemt_me_route_drop_no_conn_total 2992416
telemt_me_route_drop_channel_closed_total 1234
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2943575
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_endpoint_quarantine_total 734
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 810
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
telemt_desync_total 12652
telemt_desync_full_logged_total 3987
telemt_desync_suppressed_total 8665
telemt_desync_frames_bucket_total{bucket="1_2"} 3382
telemt_desync_frames_bucket_total{bucket="3_10"} 4611
telemt_desync_frames_bucket_total{bucket="gt_10"} 4659
telemt_pool_swap_total 115
telemt_pool_force_close_total 3530
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 662
telemt_me_draining_writers_reap_progress_total 35455
telemt_me_writer_removed_unexpected_total 607
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2536
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 33175
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3474
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 56
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 31925
telemt_me_writer_teardown_success_total{mode="normal"} 35711
telemt_me_writer_teardown_noop_total 35466
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 57577
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 59922
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 62059
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 66028
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 68988
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 70673
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 71172
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 71177
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 71177
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 71177
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 71177
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 71177
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 71177
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 378.750763
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 71177
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 662
telemt_me_refill_failed_total 42
telemt_me_writer_restored_same_endpoint_total 549
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 2932575
telemt_user_connections_current{user="hello"} 869
telemt_user_octets_from_client{user="hello"} 41965255084 (39.08 GB)
telemt_user_octets_to_client{user="hello"} 802776429080 (747.64 GB)
telemt_user_unique_ips_current{user="hello"} 403
telemt_user_unique_ips_recent_window{user="hello"} 132
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 117187.3 (32h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4014141
telemt_connections_bad_total 370900
telemt_connections_current 126
telemt_connections_me_current 126
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 100937
telemt_upstream_connect_attempt_total 73094
telemt_upstream_connect_success_total 72200
telemt_upstream_connect_fail_total 788
telemt_upstream_connect_attempts_per_request{bucket="1"} 72988
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40177
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31808
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 215
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 788
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 10186
telemt_me_reconnect_success_total 3673
telemt_me_reader_eof_total 3659
telemt_me_idle_close_by_peer_total 3659
telemt_me_route_drop_no_conn_total 3642463
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3188784
telemt_me_endpoint_quarantine_total 948
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_outage_enter_total 46
telemt_me_single_endpoint_outage_exit_total 46
telemt_me_single_endpoint_outage_reconnect_attempt_total 47
telemt_me_single_endpoint_outage_reconnect_success_total 45
telemt_me_single_endpoint_quarantine_bypass_total 47
telemt_me_single_endpoint_shadow_rotate_total 918
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 43
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 41
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_desync_total 12999
telemt_desync_full_logged_total 7295
telemt_desync_suppressed_total 5704
telemt_desync_frames_bucket_total{bucket="1_2"} 2949
telemt_desync_frames_bucket_total{bucket="3_10"} 5103
telemt_desync_frames_bucket_total{bucket="gt_10"} 4947
telemt_pool_swap_total 110
telemt_pool_force_close_total 3119
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 254
telemt_me_draining_writers_reap_progress_total 48414
telemt_me_writer_removed_unexpected_total 3588
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6334
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 45702
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2661
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 458
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 45295
telemt_me_writer_teardown_success_total{mode="normal"} 52036
telemt_me_writer_teardown_noop_total 48415
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 98489
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 99731
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 100065
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 100373
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 100436
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 100449
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 100451
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 100451
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 100451
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 100451
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 100451
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 100451
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 100451
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.637115
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 100451
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 254
telemt_me_refill_failed_total 252
telemt_me_writer_restored_same_endpoint_total 3268
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 289
telemt_user_connections_total{user="hello"} 3202151
telemt_user_connections_current{user="hello"} 126
telemt_user_octets_from_client{user="hello"} 43215291438 (40.25 GB)
telemt_user_octets_to_client{user="hello"} 794442734410 (739.88 GB)
telemt_user_msgs_from_client{user="hello"} 49767
telemt_user_msgs_to_client{user="hello"} 185105
telemt_user_unique_ips_current{user="hello"} 101
telemt_user_unique_ips_recent_window{user="hello"} 61
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 192047.1 (53h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16373463
telemt_connections_bad_total 1658802
telemt_connections_current 915
telemt_connections_me_current 915
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 398001
telemt_upstream_connect_attempt_total 86264
telemt_upstream_connect_success_total 86158
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 86175
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 42187
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 42242
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1722
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 3022
telemt_me_reconnect_success_total 1598
telemt_me_reader_eof_total 1547
telemt_me_idle_close_by_peer_total 1545
telemt_me_route_drop_no_conn_total 14050376
telemt_me_route_drop_channel_closed_total 145
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12999709
telemt_me_endpoint_quarantine_total 1285
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1448
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 45
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
telemt_desync_total 53936
telemt_desync_full_logged_total 17147
telemt_desync_suppressed_total 36789
telemt_desync_frames_bucket_total{bucket="1_2"} 12027
telemt_desync_frames_bucket_total{bucket="3_10"} 21063
telemt_desync_frames_bucket_total{bucket="gt_10"} 20846
telemt_pool_swap_total 208
telemt_pool_force_close_total 6787
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 1065
telemt_me_draining_writers_reap_progress_total 65568
telemt_me_writer_removed_unexpected_total 1488
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5567
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 60767
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 45
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 6317
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 58781
telemt_me_writer_teardown_success_total{mode="normal"} 66334
telemt_me_writer_teardown_noop_total 65621
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 120788
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 124459
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 126235
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 128627
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 130294
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 131345
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 131916
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 131946
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 131947
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 131951
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 131953
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 131955
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 131955
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 317.824197
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 131955
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1065
telemt_me_refill_failed_total 78
telemt_me_writer_restored_same_endpoint_total 1383
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 97
telemt_user_connections_total{user="hello"} 12999713
telemt_user_connections_current{user="hello"} 915
telemt_user_octets_from_client{user="hello"} 197215587557 (183.67 GB)
telemt_user_octets_to_client{user="hello"} 3498387242867 (3.18 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 427
telemt_user_unique_ips_recent_window{user="hello"} 89
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 192048.5 (53h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11912829
telemt_connections_bad_total 1241592
telemt_connections_current 505
telemt_connections_me_current 505
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 344693
telemt_upstream_connect_attempt_total 100609
telemt_upstream_connect_success_total 99280
telemt_upstream_connect_fail_total 876
telemt_upstream_connect_attempts_per_request{bucket="1"} 100156
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 53150
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 42140
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 188
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3802
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 876
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 225
telemt_me_reconnect_attempts_total 4450
telemt_me_reconnect_success_total 1900
telemt_me_reader_eof_total 1766
telemt_me_idle_close_by_peer_total 1766
telemt_me_route_drop_no_conn_total 4559995
telemt_me_route_drop_channel_closed_total 498
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8839296
telemt_me_endpoint_quarantine_total 1295
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1467
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 54
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
telemt_desync_total 38975
telemt_desync_full_logged_total 13126
telemt_desync_suppressed_total 25849
telemt_desync_frames_bucket_total{bucket="1_2"} 9657
telemt_desync_frames_bucket_total{bucket="3_10"} 14960
telemt_desync_frames_bucket_total{bucket="gt_10"} 14358
telemt_pool_swap_total 205
telemt_pool_force_close_total 6141
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 712
telemt_me_draining_writers_reap_progress_total 63776
telemt_me_writer_removed_unexpected_total 1795
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5658
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 59770
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5629
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 512
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 57635
telemt_me_writer_teardown_success_total{mode="normal"} 65428
telemt_me_writer_teardown_noop_total 63801
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 122479
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 125705
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 126854
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 128045
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 128804
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 129144
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 129219
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 129221
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 129227
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 129229
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 129229
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 129229
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 129229
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 104.452204
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 129229
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 712
telemt_me_refill_failed_total 137
telemt_me_writer_restored_same_endpoint_total 1626
telemt_me_writer_restored_fallback_total 20
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 149
telemt_user_connections_total{user="hello"} 8777040
telemt_user_connections_current{user="hello"} 505
telemt_user_octets_from_client{user="hello"} 217994320716 (203.02 GB)
telemt_user_octets_to_client{user="hello"} 3968877916883 (3.61 TB)
telemt_user_msgs_from_client{user="hello"} 124042
telemt_user_msgs_to_client{user="hello"} 140191
telemt_user_unique_ips_current{user="hello"} 251
telemt_user_unique_ips_recent_window{user="hello"} 58
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 192012.6 (53h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11082639
telemt_connections_bad_total 981129
telemt_connections_current 501
telemt_connections_me_current 501
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 345687
telemt_upstream_connect_attempt_total 84922
telemt_upstream_connect_success_total 83363
telemt_upstream_connect_fail_total 205
telemt_upstream_connect_attempts_per_request{bucket="1"} 83568
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38390
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 40577
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2033
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2363
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 205
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 1420
telemt_me_reconnect_attempts_total 5769
telemt_me_reconnect_success_total 2389
telemt_me_reader_eof_total 2134
telemt_me_idle_close_by_peer_total 2133
telemt_me_route_drop_no_conn_total 5340623
telemt_me_route_drop_channel_closed_total 383
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8374079
telemt_me_endpoint_quarantine_total 1351
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 38
telemt_me_single_endpoint_outage_reconnect_success_total 32
telemt_me_single_endpoint_quarantine_bypass_total 38
telemt_me_single_endpoint_shadow_rotate_total 1425
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 69
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
telemt_desync_total 38217
telemt_desync_full_logged_total 12658
telemt_desync_suppressed_total 25559
telemt_desync_frames_bucket_total{bucket="1_2"} 9653
telemt_desync_frames_bucket_total{bucket="3_10"} 14626
telemt_desync_frames_bucket_total{bucket="gt_10"} 13938
telemt_pool_swap_total 201
telemt_pool_force_close_total 6040
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 745
telemt_me_draining_writers_reap_progress_total 64185
telemt_me_writer_removed_unexpected_total 2284
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6416
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 59985
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5469
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 571
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 58145
telemt_me_writer_teardown_success_total{mode="normal"} 66401
telemt_me_writer_teardown_noop_total 64256
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 124816
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 127539
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 128502
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 129575
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 130176
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 130390
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 130518
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 130549
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 130557
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 130570
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 130603
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 130606
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 130657
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3174.837762
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 130657
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 745
telemt_me_refill_failed_total 179
telemt_me_writer_restored_same_endpoint_total 2079
telemt_me_writer_restored_fallback_total 17
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 188
telemt_user_connections_total{user="hello"} 8366025
telemt_user_connections_current{user="hello"} 501
telemt_user_octets_from_client{user="hello"} 192855969239 (179.61 GB)
telemt_user_octets_to_client{user="hello"} 3475694535361 (3.16 TB)
telemt_user_msgs_from_client{user="hello"} 46587
telemt_user_msgs_to_client{user="hello"} 113900
telemt_user_unique_ips_current{user="hello"} 227
telemt_user_unique_ips_recent_window{user="hello"} 53
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 62292.7 (17h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11293416
telemt_connections_bad_total 669444
telemt_connections_current 665
telemt_connections_me_current 665
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 279011
telemt_upstream_connect_attempt_total 59325
telemt_upstream_connect_success_total 56222
telemt_upstream_connect_fail_total 2038
telemt_upstream_connect_attempts_per_request{bucket="1"} 58260
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28980
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19707
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6018
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2038
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 7803
telemt_me_reconnect_success_total 1273
telemt_me_reader_eof_total 803
telemt_me_idle_close_by_peer_total 802
telemt_me_route_drop_no_conn_total 25296411
telemt_me_route_drop_channel_closed_total 59
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9366540
telemt_me_endpoint_quarantine_total 467
telemt_me_single_endpoint_outage_enter_total 94
telemt_me_single_endpoint_outage_exit_total 94
telemt_me_single_endpoint_outage_reconnect_attempt_total 179
telemt_me_single_endpoint_outage_reconnect_success_total 47
telemt_me_single_endpoint_quarantine_bypass_total 179
telemt_me_single_endpoint_shadow_rotate_total 498
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 37
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
telemt_desync_total 16433
telemt_desync_full_logged_total 4493
telemt_desync_suppressed_total 11940
telemt_desync_frames_bucket_total{bucket="1_2"} 3122
telemt_desync_frames_bucket_total{bucket="3_10"} 6699
telemt_desync_frames_bucket_total{bucket="gt_10"} 6612
telemt_pool_swap_total 65
telemt_pool_force_close_total 2086
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 490
telemt_me_draining_writers_reap_progress_total 19820
telemt_me_writer_removed_unexpected_total 1159
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2640
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18283
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1779
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 307
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17734
telemt_me_writer_teardown_success_total{mode="normal"} 20923
telemt_me_writer_teardown_noop_total 19839
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 36809
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 38606
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 39338
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 40217
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 40583
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 40706
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 40762
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 40762
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 40762
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 40762
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 40762
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 40762
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 40762
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 53.941955
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 40762
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 490
telemt_me_refill_failed_total 340
telemt_me_writer_restored_same_endpoint_total 819
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3149
telemt_me_writer_removed_unexpected_minus_restored_total 327
telemt_user_connections_total{user="hello"} 9392393
telemt_user_connections_current{user="hello"} 665
telemt_user_octets_from_client{user="hello"} 87545308046 (81.53 GB)
telemt_user_octets_to_client{user="hello"} 619674485158 (577.12 GB)
telemt_user_msgs_from_client{user="hello"} 68321
telemt_user_msgs_to_client{user="hello"} 57932
telemt_user_unique_ips_current{user="hello"} 216
telemt_user_unique_ips_recent_window{user="hello"} 203
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 192019.2 (53h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11034096
telemt_connections_bad_total 964319
telemt_connections_current 564
telemt_connections_me_current 564
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 242665
telemt_upstream_connect_attempt_total 113727
telemt_upstream_connect_success_total 112555
telemt_upstream_connect_fail_total 998
telemt_upstream_connect_attempts_per_request{bucket="1"} 113553
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 66863
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 44090
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1364
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 998
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 73045
telemt_me_reconnect_success_total 3113
telemt_me_reader_eof_total 2807
telemt_me_idle_close_by_peer_total 2805
telemt_me_route_drop_no_conn_total 5267197
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8696970
telemt_me_endpoint_quarantine_total 1302
telemt_me_single_endpoint_outage_enter_total 44
telemt_me_single_endpoint_outage_exit_total 44
telemt_me_single_endpoint_outage_reconnect_attempt_total 46
telemt_me_single_endpoint_outage_reconnect_success_total 44
telemt_me_single_endpoint_quarantine_bypass_total 46
telemt_me_single_endpoint_shadow_rotate_total 1453
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
telemt_desync_total 46337
telemt_desync_full_logged_total 15891
telemt_desync_suppressed_total 30446
telemt_desync_frames_bucket_total{bucket="1_2"} 9418
telemt_desync_frames_bucket_total{bucket="3_10"} 17734
telemt_desync_frames_bucket_total{bucket="gt_10"} 19185
telemt_pool_swap_total 197
telemt_pool_force_close_total 5754
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 666
telemt_me_draining_writers_reap_progress_total 68211
telemt_me_writer_removed_unexpected_total 2831
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6942
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 64140
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5005
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 749
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 62457
telemt_me_writer_teardown_success_total{mode="normal"} 71082
telemt_me_writer_teardown_noop_total 68212
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 137142
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 138558
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 138977
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 139250
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 139284
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 139287
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 139287
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 139290
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 139294
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 139294
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 139294
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 139294
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 139294
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.286254
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 139294
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 666
telemt_me_refill_failed_total 4304
telemt_me_writer_restored_same_endpoint_total 2626
telemt_me_writer_restored_fallback_total 52
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7367
telemt_me_writer_removed_unexpected_minus_restored_total 153
telemt_user_connections_total{user="hello"} 8699911
telemt_user_connections_current{user="hello"} 564
telemt_user_octets_from_client{user="hello"} 194842711829 (181.46 GB)
telemt_user_octets_to_client{user="hello"} 3326070471912 (3.03 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 269
telemt_user_unique_ips_recent_window{user="hello"} 85
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 128855.5 (35h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11732127
telemt_connections_bad_total 482819
telemt_connections_current 671
telemt_connections_me_current 671
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4763658
telemt_upstream_connect_attempt_total 62239
telemt_upstream_connect_success_total 61779
telemt_upstream_connect_fail_total 448
telemt_upstream_connect_attempts_per_request{bucket="1"} 62227
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32916
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28641
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 222
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 448
telemt_me_reconnect_attempts_total 49087
telemt_me_reconnect_success_total 1855
telemt_me_reader_eof_total 1531
telemt_me_idle_close_by_peer_total 1530
telemt_me_route_drop_no_conn_total 4097136
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5638828
telemt_me_endpoint_quarantine_total 879
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 989
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 25
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
telemt_desync_total 31744
telemt_desync_full_logged_total 10839
telemt_desync_suppressed_total 20905
telemt_desync_frames_bucket_total{bucket="1_2"} 6318
telemt_desync_frames_bucket_total{bucket="3_10"} 12527
telemt_desync_frames_bucket_total{bucket="gt_10"} 12899
telemt_pool_swap_total 137
telemt_pool_force_close_total 3946
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 378
telemt_me_draining_writers_reap_progress_total 47616
telemt_me_writer_removed_unexpected_total 1577
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3882
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 45359
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3505
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 441
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 43670
telemt_me_writer_teardown_success_total{mode="normal"} 49241
telemt_me_writer_teardown_noop_total 47623
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 95571
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 96327
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 96637
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 96864
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 96864
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 96864
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 96864
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 96864
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 96864
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 96864
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 96864
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 96864
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 96864
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.711347
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 96864
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 378
telemt_me_refill_failed_total 2744
telemt_me_writer_restored_same_endpoint_total 1640
telemt_me_writer_restored_fallback_total 29
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5630975
telemt_user_connections_current{user="hello"} 671
telemt_user_octets_from_client{user="hello"} 120064432948 (111.82 GB)
telemt_user_octets_to_client{user="hello"} 2186730809574 (1.99 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 322
telemt_user_unique_ips_recent_window{user="hello"} 47
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 109826.2 (30h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1541563
telemt_connections_bad_total 36789
telemt_connections_current 415
telemt_connections_me_current 415
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 31448
telemt_upstream_connect_attempt_total 51884
telemt_upstream_connect_success_total 51723
telemt_upstream_connect_fail_total 133
telemt_upstream_connect_attempts_per_request{bucket="1"} 51856
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24036
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26893
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 794
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 133
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2291
telemt_me_reconnect_success_total 937
telemt_me_reader_eof_total 926
telemt_me_idle_close_by_peer_total 926
telemt_me_route_drop_no_conn_total 521035
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1370424
telemt_me_endpoint_quarantine_total 914
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 907
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
telemt_me_writers_active_current 45
telemt_desync_total 9291
telemt_desync_full_logged_total 2681
telemt_desync_suppressed_total 6610
telemt_desync_frames_bucket_total{bucket="1_2"} 2707
telemt_desync_frames_bucket_total{bucket="3_10"} 3534
telemt_desync_frames_bucket_total{bucket="gt_10"} 3050
telemt_pool_swap_total 118
telemt_pool_force_close_total 3003
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 171
telemt_me_draining_writers_reap_progress_total 43950
telemt_me_writer_removed_unexpected_total 892
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3356
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 41527
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2915
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 40947
telemt_me_writer_teardown_success_total{mode="normal"} 44883
telemt_me_writer_teardown_noop_total 43954
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 87856
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 88570
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 88800
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 88837
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 88837
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 88837
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 88837
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 88837
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 88837
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 88837
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 88837
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 88837
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 88837
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.355110
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 88837
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 171
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 798
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 73
telemt_user_connections_total{user="hello"} 1366223
telemt_user_connections_current{user="hello"} 415
telemt_user_octets_from_client{user="hello"} 26184263245 (24.39 GB)
telemt_user_octets_to_client{user="hello"} 581457389163 (541.52 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 191
telemt_user_unique_ips_recent_window{user="hello"} 54
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 192023.8 (53h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13353975
telemt_connections_bad_total 1610549
telemt_connections_current 586
telemt_connections_me_current 586
telemt_handshake_timeouts_total 389940
telemt_upstream_connect_attempt_total 76186
telemt_upstream_connect_success_total 75832
telemt_upstream_connect_fail_total 218
telemt_upstream_connect_attempts_per_request{bucket="1"} 76050
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37473
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38255
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 100
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 218
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 3035
telemt_me_reconnect_success_total 1516
telemt_me_reader_eof_total 1500
telemt_me_idle_close_by_peer_total 1500
telemt_me_route_drop_no_conn_total 4485757
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 42
telemt_me_route_drop_queue_full_profile_total{profile="high"} 42
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10064700
telemt_me_endpoint_quarantine_total 1389
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1455
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
telemt_me_writers_active_current 44
telemt_desync_total 42206
telemt_desync_full_logged_total 13782
telemt_desync_suppressed_total 28424
telemt_desync_frames_bucket_total{bucket="1_2"} 10250
telemt_desync_frames_bucket_total{bucket="3_10"} 15503
telemt_desync_frames_bucket_total{bucket="gt_10"} 16453
telemt_pool_swap_total 213
telemt_pool_force_close_total 5639
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 681
telemt_me_draining_writers_reap_progress_total 68913
telemt_me_writer_removed_unexpected_total 1437
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5393
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 65010
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5465
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 63274
telemt_me_writer_teardown_success_total{mode="normal"} 70403
telemt_me_writer_teardown_noop_total 68915
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 136700
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 138426
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 138809
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 139185
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 139305
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 139318
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 139318
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 139318
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 139318
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 139318
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 139318
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 139318
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 139318
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.814883
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 139318
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 681
telemt_me_refill_failed_total 82
telemt_me_writer_restored_same_endpoint_total 1330
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 91
telemt_user_connections_total{user="hello"} 10031389
telemt_user_connections_current{user="hello"} 586
telemt_user_octets_from_client{user="hello"} 194910254276 (181.52 GB)
telemt_user_octets_to_client{user="hello"} 4445434839424 (4.04 TB)
telemt_user_unique_ips_current{user="hello"} 260
telemt_user_unique_ips_recent_window{user="hello"} 49
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 192020.4 (53h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11670253
telemt_connections_bad_total 1364453
telemt_connections_current 543
telemt_connections_me_current 543
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 312205
telemt_upstream_connect_attempt_total 103729
telemt_upstream_connect_success_total 102830
telemt_upstream_connect_fail_total 691
telemt_upstream_connect_attempts_per_request{bucket="1"} 103521
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 55992
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 43857
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2068
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 691
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 10639
telemt_me_reconnect_success_total 2622
telemt_me_reader_eof_total 2432
telemt_me_idle_close_by_peer_total 2431
telemt_me_seq_mismatch_total 100
telemt_me_route_drop_no_conn_total 5653313
telemt_me_route_drop_channel_closed_total 354
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8978588
telemt_me_endpoint_quarantine_total 1571
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 53
telemt_me_single_endpoint_outage_exit_total 53
telemt_me_single_endpoint_outage_reconnect_attempt_total 53
telemt_me_single_endpoint_outage_reconnect_success_total 51
telemt_me_single_endpoint_quarantine_bypass_total 53
telemt_me_single_endpoint_shadow_rotate_total 1458
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 57
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
telemt_desync_total 41845
telemt_desync_full_logged_total 13477
telemt_desync_suppressed_total 28368
telemt_desync_frames_bucket_total{bucket="1_2"} 10810
telemt_desync_frames_bucket_total{bucket="3_10"} 15389
telemt_desync_frames_bucket_total{bucket="gt_10"} 15646
telemt_pool_swap_total 203
telemt_pool_force_close_total 5413
telemt_pool_stale_pick_total 390
telemt_me_writer_close_signal_drop_total 668
telemt_me_draining_writers_reap_progress_total 68983
telemt_me_writer_removed_unexpected_total 2474
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6774
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 64770
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4942
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 63570
telemt_me_writer_teardown_success_total{mode="normal"} 71544
telemt_me_writer_teardown_noop_total 68988
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 137842
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 139624
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 140163
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 140482
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 140532
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 140532
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 140532
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 140532
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 140532
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 140532
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 140532
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 140532
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 140532
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.495145
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 140532
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 668
telemt_me_refill_failed_total 415
telemt_me_writer_restored_same_endpoint_total 2106
telemt_me_writer_restored_fallback_total 135
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 135
telemt_me_writer_removed_unexpected_minus_restored_total 233
telemt_user_connections_total{user="hello"} 8983159
telemt_user_connections_current{user="hello"} 543
telemt_user_octets_from_client{user="hello"} 157516186884 (146.70 GB)
telemt_user_octets_to_client{user="hello"} 3496171950254 (3.18 TB)
telemt_user_msgs_from_client{user="hello"} 103592
telemt_user_msgs_to_client{user="hello"} 254638
telemt_user_unique_ips_current{user="hello"} 261
telemt_user_unique_ips_recent_window{user="hello"} 61
```