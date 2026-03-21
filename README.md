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

# Server Metrics 2026-03-21 19:58:02 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 84129.0 (23h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3026790
telemt_connections_bad_total 176570
telemt_connections_current 975
telemt_connections_me_current 975
telemt_relay_adaptive_promotions_total 3
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 92688
telemt_upstream_connect_attempt_total 34450
telemt_upstream_connect_success_total 34307
telemt_upstream_connect_fail_total 100
telemt_upstream_connect_attempts_per_request{bucket="1"} 34407
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13868
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20318
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 53
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 68
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 100
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 107
telemt_me_reconnect_attempts_total 1858
telemt_me_reconnect_success_total 748
telemt_me_reader_eof_total 716
telemt_me_idle_close_by_peer_total 716
telemt_me_route_drop_no_conn_total 2609277
telemt_me_route_drop_channel_closed_total 837
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2447507
telemt_me_writer_pick_total{mode="p2c",result="full"} 26
telemt_me_endpoint_quarantine_total 569
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 657
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
telemt_desync_total 9731
telemt_desync_full_logged_total 3402
telemt_desync_suppressed_total 6329
telemt_desync_frames_bucket_total{bucket="1_2"} 2125
telemt_desync_frames_bucket_total{bucket="3_10"} 3689
telemt_desync_frames_bucket_total{bucket="gt_10"} 3917
telemt_pool_swap_total 91
telemt_pool_force_close_total 2761
telemt_pool_stale_pick_total 31
telemt_me_writer_close_signal_drop_total 636
telemt_me_draining_writers_reap_progress_total 28198
telemt_me_writer_removed_unexpected_total 698
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2375
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26261
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2622
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 139
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 25437
telemt_me_writer_teardown_success_total{mode="normal"} 28636
telemt_me_writer_teardown_noop_total 28206
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 46443
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 48317
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 49936
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 52856
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 55266
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 56465
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 56812
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 56837
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 56841
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 56842
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 56842
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 56842
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 56842
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 296.506454
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 56842
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 636
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 642
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 48
telemt_user_connections_total{user="hello"} 2447193
telemt_user_connections_current{user="hello"} 975
telemt_user_octets_from_client{user="hello"} 36255880641 (33.77 GB)
telemt_user_octets_to_client{user="hello"} 615075150946 (572.83 GB)
telemt_user_msgs_from_client{user="hello"} 7227
telemt_user_msgs_to_client{user="hello"} 6949
telemt_user_unique_ips_current{user="hello"} 403
telemt_user_unique_ips_recent_window{user="hello"} 125
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 9266.8 (2h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 386347
telemt_connections_bad_total 17831
telemt_connections_current 928
telemt_connections_me_current 928
telemt_handshake_timeouts_total 13408
telemt_upstream_connect_attempt_total 3724
telemt_upstream_connect_success_total 3641
telemt_upstream_connect_fail_total 72
telemt_upstream_connect_attempts_per_request{bucket="1"} 3713
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1585
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2043
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 72
telemt_me_reconnect_attempts_total 172
telemt_me_reconnect_success_total 126
telemt_me_reader_eof_total 102
telemt_me_idle_close_by_peer_total 102
telemt_me_route_drop_no_conn_total 247548
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 318222
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
telemt_desync_total 1378
telemt_desync_full_logged_total 772
telemt_desync_suppressed_total 606
telemt_desync_frames_bucket_total{bucket="1_2"} 279
telemt_desync_frames_bucket_total{bucket="3_10"} 511
telemt_desync_frames_bucket_total{bucket="gt_10"} 588
telemt_pool_swap_total 10
telemt_pool_force_close_total 309
telemt_me_writer_close_signal_drop_total 30
telemt_me_draining_writers_reap_progress_total 3207
telemt_me_writer_removed_unexpected_total 96
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 286
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 3010
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 302
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 2898
telemt_me_writer_teardown_success_total{mode="normal"} 3296
telemt_me_writer_teardown_noop_total 3207
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 6276
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 6427
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 6456
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 6503
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 6503
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 6503
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 6503
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 6503
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 6503
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 6503
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 6503
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 6503
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 6503
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.406063
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 6503
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 30
telemt_me_refill_failed_total 2
telemt_me_writer_restored_same_endpoint_total 86
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 317853
telemt_user_connections_current{user="hello"} 928
telemt_user_octets_from_client{user="hello"} 5128824556 (4.78 GB)
telemt_user_octets_to_client{user="hello"} 89575092332 (83.42 GB)
telemt_user_unique_ips_current{user="hello"} 603
telemt_user_unique_ips_recent_window{user="hello"} 360
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 84126.7 (23h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6676835
telemt_connections_bad_total 513127
telemt_connections_current 3484
telemt_connections_me_current 3484
telemt_handshake_timeouts_total 210017
telemt_upstream_connect_attempt_total 30273
telemt_upstream_connect_success_total 30211
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 30217
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13594
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16487
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 124
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1277
telemt_me_reconnect_success_total 655
telemt_me_reader_eof_total 664
telemt_me_idle_close_by_peer_total 664
telemt_me_route_drop_no_conn_total 4292826
telemt_me_route_drop_channel_closed_total 61
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5492734
telemt_me_endpoint_quarantine_total 521
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 625
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
telemt_desync_total 22420
telemt_desync_full_logged_total 7465
telemt_desync_suppressed_total 14955
telemt_desync_frames_bucket_total{bucket="1_2"} 4703
telemt_desync_frames_bucket_total{bucket="3_10"} 8930
telemt_desync_frames_bucket_total{bucket="gt_10"} 8787
telemt_pool_swap_total 90
telemt_pool_force_close_total 3016
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 492
telemt_me_draining_writers_reap_progress_total 27558
telemt_me_writer_removed_unexpected_total 639
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2382
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 25465
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 37
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2786
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 230
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 24542
telemt_me_writer_teardown_success_total{mode="normal"} 27847
telemt_me_writer_teardown_noop_total 27595
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 50345
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 51933
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 52756
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 53934
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 54717
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 55182
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 55431
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 55442
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 55442
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 55442
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 55442
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 55442
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 55442
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 131.019449
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 55442
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 492
telemt_me_refill_failed_total 32
telemt_me_writer_restored_same_endpoint_total 590
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 44
telemt_user_connections_total{user="hello"} 5486103
telemt_user_connections_current{user="hello"} 3484
telemt_user_octets_from_client{user="hello"} 91647097904 (85.35 GB)
telemt_user_octets_to_client{user="hello"} 1707898767380 (1.55 TB)
telemt_user_unique_ips_current{user="hello"} 1433
telemt_user_unique_ips_recent_window{user="hello"} 496
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 84128.2 (23h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5393202
telemt_connections_bad_total 514139
telemt_connections_current 3586
telemt_connections_me_current 3586
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 178261
telemt_upstream_connect_attempt_total 34456
telemt_upstream_connect_success_total 34141
telemt_upstream_connect_fail_total 161
telemt_upstream_connect_attempts_per_request{bucket="1"} 34302
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17292
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16282
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 540
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 161
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 1644
telemt_me_reconnect_success_total 687
telemt_me_reader_eof_total 659
telemt_me_idle_close_by_peer_total 659
telemt_me_route_drop_no_conn_total 1867567
telemt_me_route_drop_channel_closed_total 213
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4039404
telemt_me_endpoint_quarantine_total 516
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 642
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
telemt_me_writers_active_current 45
telemt_desync_total 18980
telemt_desync_full_logged_total 6298
telemt_desync_suppressed_total 12682
telemt_desync_frames_bucket_total{bucket="1_2"} 4623
telemt_desync_frames_bucket_total{bucket="3_10"} 7351
telemt_desync_frames_bucket_total{bucket="gt_10"} 7006
telemt_pool_swap_total 92
telemt_pool_force_close_total 2789
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 312
telemt_me_draining_writers_reap_progress_total 26412
telemt_me_writer_removed_unexpected_total 639
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2305
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 24674
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2598
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 191
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 23623
telemt_me_writer_teardown_success_total{mode="normal"} 26979
telemt_me_writer_teardown_noop_total 26417
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 50540
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 51889
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 52366
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 52882
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 53227
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 53383
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 53396
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 53396
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 53396
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 53396
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 53396
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 53396
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 53396
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 40.599126
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 53396
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 312
telemt_me_refill_failed_total 51
telemt_me_writer_restored_same_endpoint_total 587
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 44
telemt_user_connections_total{user="hello"} 4036495
telemt_user_connections_current{user="hello"} 3586
telemt_user_octets_from_client{user="hello"} 120183271977 (111.93 GB)
telemt_user_octets_to_client{user="hello"} 1831384631935 (1.67 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1347
telemt_user_unique_ips_recent_window{user="hello"} 454
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 84092.4 (23h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5320130
telemt_connections_bad_total 479770
telemt_connections_current 3252
telemt_connections_me_current 3252
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 161242
telemt_upstream_connect_attempt_total 40836
telemt_upstream_connect_success_total 40572
telemt_upstream_connect_fail_total 134
telemt_upstream_connect_attempts_per_request{bucket="1"} 40706
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21495
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17716
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 327
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1034
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 134
telemt_me_keepalive_timeout_total 58
telemt_me_reconnect_attempts_total 1704
telemt_me_reconnect_success_total 740
telemt_me_reader_eof_total 684
telemt_me_idle_close_by_peer_total 684
telemt_me_route_drop_no_conn_total 1928737
telemt_me_route_drop_channel_closed_total 93
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4019597
telemt_me_endpoint_quarantine_total 569
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 629
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
telemt_desync_total 18701
telemt_desync_full_logged_total 6097
telemt_desync_suppressed_total 12604
telemt_desync_frames_bucket_total{bucket="1_2"} 4628
telemt_desync_frames_bucket_total{bucket="3_10"} 7096
telemt_desync_frames_bucket_total{bucket="gt_10"} 6977
telemt_pool_swap_total 90
telemt_pool_force_close_total 2653
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 328
telemt_me_draining_writers_reap_progress_total 27831
telemt_me_writer_removed_unexpected_total 653
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2377
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26128
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2443
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 210
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 25178
telemt_me_writer_teardown_success_total{mode="normal"} 28505
telemt_me_writer_teardown_noop_total 27841
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 54216
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 55368
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 55736
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 56149
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 56323
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 56343
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 56346
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 56346
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 56346
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 56346
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 56346
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 56346
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 56346
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 20.668931
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 56346
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 328
telemt_me_refill_failed_total 53
telemt_me_writer_restored_same_endpoint_total 636
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 13
telemt_user_connections_total{user="hello"} 4022093
telemt_user_connections_current{user="hello"} 3252
telemt_user_octets_from_client{user="hello"} 117159217943 (109.11 GB)
telemt_user_octets_to_client{user="hello"} 1831376454815 (1.67 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 1297
telemt_user_unique_ips_recent_window{user="hello"} 425
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 84131.4 (23h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18533742
telemt_connections_bad_total 1170297
telemt_connections_current 4607
telemt_connections_me_current 4607
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 519754
telemt_upstream_connect_attempt_total 173893
telemt_upstream_connect_success_total 157035
telemt_upstream_connect_fail_total 15493
telemt_upstream_connect_attempts_per_request{bucket="1"} 172528
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 111995
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35197
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1024
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8819
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15493
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 4595
telemt_me_reconnect_success_total 1721
telemt_me_reader_eof_total 1178
telemt_me_idle_close_by_peer_total 1177
telemt_me_route_drop_no_conn_total 37928561
telemt_me_route_drop_channel_closed_total 108
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 15268033
telemt_me_endpoint_quarantine_total 618
telemt_me_single_endpoint_outage_enter_total 98
telemt_me_single_endpoint_outage_exit_total 98
telemt_me_single_endpoint_outage_reconnect_attempt_total 216
telemt_me_single_endpoint_outage_reconnect_success_total 47
telemt_me_single_endpoint_quarantine_bypass_total 216
telemt_me_single_endpoint_shadow_rotate_total 652
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
telemt_me_writers_active_current 45
telemt_desync_total 28234
telemt_desync_full_logged_total 8346
telemt_desync_suppressed_total 19888
telemt_desync_frames_bucket_total{bucket="1_2"} 6045
telemt_desync_frames_bucket_total{bucket="3_10"} 12606
telemt_desync_frames_bucket_total{bucket="gt_10"} 9583
telemt_pool_swap_total 86
telemt_pool_force_close_total 2858
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 639
telemt_me_draining_writers_reap_progress_total 25964
telemt_me_writer_removed_unexpected_total 1630
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3465
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 23887
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 15
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2414
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 444
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 23106
telemt_me_writer_teardown_success_total{mode="normal"} 27352
telemt_me_writer_teardown_noop_total 25980
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 47640
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 49673
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 50793
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 52138
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 52933
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 53244
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 53313
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 53315
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 53318
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 53323
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 53323
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 53327
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 53332
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 198.502794
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 53332
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 639
telemt_me_refill_failed_total 98
telemt_me_writer_restored_same_endpoint_total 1192
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 160
telemt_me_writer_removed_unexpected_minus_restored_total 427
telemt_user_connections_total{user="hello"} 15386984
telemt_user_connections_current{user="hello"} 4607
telemt_user_octets_from_client{user="hello"} 139406466951 (129.83 GB)
telemt_user_octets_to_client{user="hello"} 944058980323 (879.22 GB)
telemt_user_msgs_from_client{user="hello"} 352315
telemt_user_msgs_to_client{user="hello"} 633668
telemt_user_unique_ips_current{user="hello"} 1701
telemt_user_unique_ips_recent_window{user="hello"} 827
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 84099.1 (23h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5258711
telemt_connections_bad_total 510150
telemt_connections_current 3481
telemt_connections_me_current 3481
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 108240
telemt_upstream_connect_attempt_total 43895
telemt_upstream_connect_success_total 43436
telemt_upstream_connect_fail_total 378
telemt_upstream_connect_attempts_per_request{bucket="1"} 43814
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25185
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17926
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 324
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 378
telemt_me_reconnect_attempts_total 3458
telemt_me_reconnect_success_total 1208
telemt_me_reader_eof_total 1182
telemt_me_idle_close_by_peer_total 1182
telemt_me_route_drop_no_conn_total 2214711
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 36
telemt_me_route_drop_queue_full_profile_total{profile="high"} 36
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4073999
telemt_me_endpoint_quarantine_total 506
telemt_me_single_endpoint_outage_enter_total 13
telemt_me_single_endpoint_outage_exit_total 13
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 13
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 625
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
telemt_desync_total 20096
telemt_desync_full_logged_total 6972
telemt_desync_suppressed_total 13124
telemt_desync_frames_bucket_total{bucket="1_2"} 3855
telemt_desync_frames_bucket_total{bucket="3_10"} 7883
telemt_desync_frames_bucket_total{bucket="gt_10"} 8358
telemt_pool_swap_total 85
telemt_pool_force_close_total 2499
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 310
telemt_me_draining_writers_reap_progress_total 28600
telemt_me_writer_removed_unexpected_total 1145
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2906
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26851
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2155
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 344
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26101
telemt_me_writer_teardown_success_total{mode="normal"} 29757
telemt_me_writer_teardown_noop_total 28601
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 57348
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 58009
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 58235
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 58326
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 58355
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 58358
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 58358
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 58358
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 58358
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 58358
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 58358
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 58358
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 58358
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 6.737886
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 58358
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 310
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 1026
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 104
telemt_user_connections_total{user="hello"} 4064449
telemt_user_connections_current{user="hello"} 3481
telemt_user_octets_from_client{user="hello"} 108483264913 (101.03 GB)
telemt_user_octets_to_client{user="hello"} 1637888447971 (1.49 TB)
telemt_user_msgs_from_client{user="hello"} 59697
telemt_user_msgs_to_client{user="hello"} 266554
telemt_user_unique_ips_current{user="hello"} 1412
telemt_user_unique_ips_recent_window{user="hello"} 413
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 20934.7 (5h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2865775
telemt_connections_bad_total 107862
telemt_connections_current 2748
telemt_connections_me_current 2748
telemt_handshake_timeouts_total 1232038
telemt_upstream_connect_attempt_total 6740
telemt_upstream_connect_success_total 6643
telemt_upstream_connect_fail_total 91
telemt_upstream_connect_attempts_per_request{bucket="1"} 6734
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2927
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3669
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 47
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 91
telemt_me_reconnect_attempts_total 668
telemt_me_reconnect_success_total 201
telemt_me_reader_eof_total 186
telemt_me_idle_close_by_peer_total 186
telemt_me_route_drop_no_conn_total 860949
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1355117
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
telemt_desync_total 7410
telemt_desync_full_logged_total 2428
telemt_desync_suppressed_total 4982
telemt_desync_frames_bucket_total{bucket="1_2"} 1327
telemt_desync_frames_bucket_total{bucket="3_10"} 2781
telemt_desync_frames_bucket_total{bucket="gt_10"} 3302
telemt_pool_swap_total 22
telemt_pool_force_close_total 710
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 69
telemt_me_draining_writers_reap_progress_total 5860
telemt_me_writer_removed_unexpected_total 183
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 559
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 5489
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 622
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 5150
telemt_me_writer_teardown_success_total{mode="normal"} 6048
telemt_me_writer_teardown_noop_total 5860
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 11660
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 11789
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 11832
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 11908
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 11908
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 11908
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 11908
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 11908
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 11908
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 11908
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 11908
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 11908
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 11908
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.954060
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 11908
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 69
telemt_me_refill_failed_total 27
telemt_me_writer_restored_same_endpoint_total 166
telemt_me_async_recovery_trigger_total 6
telemt_me_writer_removed_unexpected_minus_restored_total 17
telemt_user_connections_total{user="hello"} 1351499
telemt_user_connections_current{user="hello"} 2748
telemt_user_octets_from_client{user="hello"} 41906894952 (39.03 GB)
telemt_user_octets_to_client{user="hello"} 546335710072 (508.81 GB)
telemt_user_unique_ips_current{user="hello"} 1124
telemt_user_unique_ips_recent_window{user="hello"} 416
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 1906.1 (0h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18590
telemt_connections_bad_total 28
telemt_connections_current 696
telemt_connections_me_current 696
telemt_handshake_timeouts_total 445
telemt_upstream_connect_attempt_total 839
telemt_upstream_connect_success_total 837
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 839
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 338
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 482
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 7
telemt_me_reconnect_success_total 6
telemt_me_reader_eof_total 6
telemt_me_idle_close_by_peer_total 6
telemt_me_route_drop_no_conn_total 5344
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 17083
telemt_me_endpoint_quarantine_total 11
telemt_me_single_endpoint_shadow_rotate_total 21
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
telemt_me_writers_active_current 46
telemt_desync_total 83
telemt_desync_full_logged_total 24
telemt_desync_suppressed_total 59
telemt_desync_frames_bucket_total{bucket="1_2"} 33
telemt_desync_frames_bucket_total{bucket="3_10"} 30
telemt_desync_frames_bucket_total{bucket="gt_10"} 20
telemt_pool_swap_total 2
telemt_pool_force_close_total 29
telemt_me_draining_writers_reap_progress_total 660
telemt_me_writer_removed_unexpected_total 6
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 35
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 631
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 29
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 631
telemt_me_writer_teardown_success_total{mode="normal"} 666
telemt_me_writer_teardown_noop_total 660
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 1326
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 1326
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 1326
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 1326
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 1326
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 1326
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 1326
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 1326
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 1326
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 1326
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 1326
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 1326
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 1326
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.019499
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 1326
telemt_me_writer_restored_same_endpoint_total 6
telemt_user_connections_total{user="hello"} 17074
telemt_user_connections_current{user="hello"} 696
telemt_user_octets_from_client{user="hello"} 728824012 (695.06 MB)
telemt_user_octets_to_client{user="hello"} 13987721152 (13.03 GB)
telemt_user_unique_ips_current{user="hello"} 281
telemt_user_unique_ips_recent_window{user="hello"} 95
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 84103.3 (23h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6178384
telemt_connections_bad_total 607604
telemt_connections_current 4241
telemt_connections_me_current 4241
telemt_handshake_timeouts_total 182004
telemt_upstream_connect_attempt_total 32069
telemt_upstream_connect_success_total 31940
telemt_upstream_connect_fail_total 92
telemt_upstream_connect_attempts_per_request{bucket="1"} 32032
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15812
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16089
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 92
telemt_me_reconnect_attempts_total 1354
telemt_me_reconnect_success_total 693
telemt_me_reader_eof_total 666
telemt_me_idle_close_by_peer_total 666
telemt_me_route_drop_no_conn_total 1927368
telemt_me_route_drop_channel_closed_total 51
telemt_me_route_drop_queue_full_total 21
telemt_me_route_drop_queue_full_profile_total{profile="high"} 21
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4770343
telemt_me_endpoint_quarantine_total 564
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 641
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
telemt_desync_total 18037
telemt_desync_full_logged_total 5960
telemt_desync_suppressed_total 12077
telemt_desync_frames_bucket_total{bucket="1_2"} 4411
telemt_desync_frames_bucket_total{bucket="3_10"} 6591
telemt_desync_frames_bucket_total{bucket="gt_10"} 7035
telemt_pool_swap_total 93
telemt_pool_force_close_total 2527
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 316
telemt_me_draining_writers_reap_progress_total 28790
telemt_me_writer_removed_unexpected_total 650
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2339
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27107
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2456
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 71
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26263
telemt_me_writer_teardown_success_total{mode="normal"} 29446
telemt_me_writer_teardown_noop_total 28791
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 57090
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 57829
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 57972
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 58149
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 58237
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 58237
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 58237
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 58237
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 58237
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 58237
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 58237
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 58237
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 58237
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 9.388780
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 58237
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 316
telemt_me_refill_failed_total 34
telemt_me_writer_restored_same_endpoint_total 619
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 26
telemt_user_connections_total{user="hello"} 4746710
telemt_user_connections_current{user="hello"} 4241
telemt_user_octets_from_client{user="hello"} 93965362612 (87.51 GB)
telemt_user_octets_to_client{user="hello"} 2198278810260 (2.00 TB)
telemt_user_unique_ips_current{user="hello"} 1501
telemt_user_unique_ips_recent_window{user="hello"} 467
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 84100.0 (23h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5240279
telemt_connections_bad_total 484496
telemt_connections_current 3919
telemt_connections_me_current 3919
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 152368
telemt_upstream_connect_attempt_total 48436
telemt_upstream_connect_success_total 48079
telemt_upstream_connect_fail_total 298
telemt_upstream_connect_attempts_per_request{bucket="1"} 48377
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29011
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17937
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 613
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 298
telemt_me_reconnect_attempts_total 4433
telemt_me_reconnect_success_total 976
telemt_me_reader_eof_total 864
telemt_me_idle_close_by_peer_total 864
telemt_me_seq_mismatch_total 36
telemt_me_route_drop_no_conn_total 1982809
telemt_me_route_drop_channel_closed_total 180
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4152258
telemt_me_endpoint_quarantine_total 670
telemt_me_single_endpoint_outage_enter_total 25
telemt_me_single_endpoint_outage_exit_total 25
telemt_me_single_endpoint_outage_reconnect_attempt_total 25
telemt_me_single_endpoint_outage_reconnect_success_total 24
telemt_me_single_endpoint_quarantine_bypass_total 25
telemt_me_single_endpoint_shadow_rotate_total 641
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
telemt_desync_total 16560
telemt_desync_full_logged_total 5611
telemt_desync_suppressed_total 10949
telemt_desync_frames_bucket_total{bucket="1_2"} 4085
telemt_desync_frames_bucket_total{bucket="3_10"} 6097
telemt_desync_frames_bucket_total{bucket="gt_10"} 6378
telemt_pool_swap_total 91
telemt_pool_force_close_total 2462
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 312
telemt_me_draining_writers_reap_progress_total 28001
telemt_me_writer_removed_unexpected_total 875
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2804
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26111
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2270
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 192
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 25539
telemt_me_writer_teardown_success_total{mode="normal"} 28915
telemt_me_writer_teardown_noop_total 28003
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 55569
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 56443
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 56707
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 56886
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 56918
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 56918
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 56918
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 56918
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 56918
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 56918
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 56918
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 56918
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 56918
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 9.253275
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 56918
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 312
telemt_me_refill_failed_total 197
telemt_me_writer_restored_same_endpoint_total 753
telemt_me_writer_restored_fallback_total 46
telemt_me_async_recovery_trigger_total 59
telemt_me_writer_removed_unexpected_minus_restored_total 76
telemt_user_connections_total{user="hello"} 4157172
telemt_user_connections_current{user="hello"} 3919
telemt_user_octets_from_client{user="hello"} 78031139801 (72.67 GB)
telemt_user_octets_to_client{user="hello"} 1733635655844 (1.58 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1436
telemt_user_unique_ips_recent_window{user="hello"} 477
```