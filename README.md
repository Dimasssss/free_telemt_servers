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

# Server Metrics 2026-03-23 01:10:57 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 101073.8 (28h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3517191
telemt_connections_bad_total 310107
telemt_connections_current 890
telemt_connections_me_current 890
telemt_handshake_timeouts_total 109475
telemt_upstream_connect_attempt_total 37557
telemt_upstream_connect_success_total 37556
telemt_upstream_connect_attempts_per_request{bucket="1"} 37556
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13045
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24379
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 92
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 451
telemt_me_reconnect_attempts_total 1396
telemt_me_reconnect_success_total 602
telemt_me_reader_eof_total 618
telemt_me_idle_close_by_peer_total 618
telemt_me_route_drop_no_conn_total 2984492
telemt_me_route_drop_channel_closed_total 1233
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2904787
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_endpoint_quarantine_total 712
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 788
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 28
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
telemt_desync_total 12460
telemt_desync_full_logged_total 3908
telemt_desync_suppressed_total 8552
telemt_desync_frames_bucket_total{bucket="1_2"} 3360
telemt_desync_frames_bucket_total{bucket="3_10"} 4536
telemt_desync_frames_bucket_total{bucket="gt_10"} 4564
telemt_pool_swap_total 112
telemt_pool_force_close_total 3457
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 654
telemt_me_draining_writers_reap_progress_total 34391
telemt_me_writer_removed_unexpected_total 596
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2476
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 32159
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3401
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 56
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 30934
telemt_me_writer_teardown_success_total{mode="normal"} 34635
telemt_me_writer_teardown_noop_total 34402
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 55490
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 57822
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 59949
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 63892
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 66848
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 68533
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 69032
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 69037
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 69037
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 69037
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 69037
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 69037
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 69037
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 378.023260
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 69037
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 654
telemt_me_refill_failed_total 42
telemt_me_writer_restored_same_endpoint_total 538
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 2893866
telemt_user_connections_current{user="hello"} 890
telemt_user_octets_from_client{user="hello"} 41298039416 (38.46 GB)
telemt_user_octets_to_client{user="hello"} 793158657320 (738.69 GB)
telemt_user_unique_ips_current{user="hello"} 414
telemt_user_unique_ips_recent_window{user="hello"} 128
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 114439.8 (31h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4000508
telemt_connections_bad_total 368143
telemt_connections_current 359
telemt_connections_me_current 359
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 100743
telemt_upstream_connect_attempt_total 71531
telemt_upstream_connect_success_total 70681
telemt_upstream_connect_fail_total 757
telemt_upstream_connect_attempts_per_request{bucket="1"} 71438
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39483
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30987
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 211
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 757
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 10095
telemt_me_reconnect_success_total 3607
telemt_me_reader_eof_total 3609
telemt_me_idle_close_by_peer_total 3609
telemt_me_route_drop_no_conn_total 3640938
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3178625
telemt_me_endpoint_quarantine_total 911
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_outage_enter_total 44
telemt_me_single_endpoint_outage_exit_total 44
telemt_me_single_endpoint_outage_reconnect_attempt_total 44
telemt_me_single_endpoint_outage_reconnect_success_total 43
telemt_me_single_endpoint_quarantine_bypass_total 44
telemt_me_single_endpoint_shadow_rotate_total 891
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 42
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
telemt_me_writers_active_current 39
telemt_desync_total 12959
telemt_desync_full_logged_total 7266
telemt_desync_suppressed_total 5693
telemt_desync_frames_bucket_total{bucket="1_2"} 2940
telemt_desync_frames_bucket_total{bucket="3_10"} 5080
telemt_desync_frames_bucket_total{bucket="gt_10"} 4939
telemt_pool_swap_total 107
telemt_pool_force_close_total 3052
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 252
telemt_me_draining_writers_reap_progress_total 47106
telemt_me_writer_removed_unexpected_total 3539
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6200
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 44478
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2594
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 458
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 44054
telemt_me_writer_teardown_success_total{mode="normal"} 50678
telemt_me_writer_teardown_noop_total 47107
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 95823
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 97065
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 97399
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 97707
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 97770
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 97783
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 97785
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 97785
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 97785
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 97785
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 97785
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 97785
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 97785
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.614344
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 97785
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 252
telemt_me_refill_failed_total 251
telemt_me_writer_restored_same_endpoint_total 3225
telemt_me_writer_restored_fallback_total 29
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 285
telemt_user_connections_total{user="hello"} 3191928
telemt_user_connections_current{user="hello"} 359
telemt_user_octets_from_client{user="hello"} 43071017771 (40.11 GB)
telemt_user_octets_to_client{user="hello"} 791410421124 (737.06 GB)
telemt_user_msgs_from_client{user="hello"} 49657
telemt_user_msgs_to_client{user="hello"} 185005
telemt_user_unique_ips_current{user="hello"} 231
telemt_user_unique_ips_recent_window{user="hello"} 45
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 189299.8 (52h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16331118
telemt_connections_bad_total 1644825
telemt_connections_current 740
telemt_connections_me_current 740
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 397354
telemt_upstream_connect_attempt_total 84820
telemt_upstream_connect_success_total 84715
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 84732
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 41553
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 41438
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1717
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2998
telemt_me_reconnect_success_total 1574
telemt_me_reader_eof_total 1522
telemt_me_idle_close_by_peer_total 1520
telemt_me_route_drop_no_conn_total 14045772
telemt_me_route_drop_channel_closed_total 145
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12974385
telemt_me_endpoint_quarantine_total 1257
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1426
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
telemt_me_writers_active_current 43
telemt_desync_total 53816
telemt_desync_full_logged_total 17091
telemt_desync_suppressed_total 36725
telemt_desync_frames_bucket_total{bucket="1_2"} 11997
telemt_desync_frames_bucket_total{bucket="3_10"} 20999
telemt_desync_frames_bucket_total{bucket="gt_10"} 20820
telemt_pool_swap_total 205
telemt_pool_force_close_total 6722
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 1063
telemt_me_draining_writers_reap_progress_total 64251
telemt_me_writer_removed_unexpected_total 1465
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5491
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 59501
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 45
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 6252
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 57529
telemt_me_writer_teardown_success_total{mode="normal"} 64992
telemt_me_writer_teardown_noop_total 64304
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 118136
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 121800
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 123576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 125968
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 127635
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 128686
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 129257
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 129287
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 129288
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 129292
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 129294
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 129296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 129296
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 317.775217
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 129296
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1063
telemt_me_refill_failed_total 78
telemt_me_writer_restored_same_endpoint_total 1362
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 95
telemt_user_connections_total{user="hello"} 12974414
telemt_user_connections_current{user="hello"} 740
telemt_user_octets_from_client{user="hello"} 191120515677 (177.99 GB)
telemt_user_octets_to_client{user="hello"} 3489013342607 (3.17 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 368
telemt_user_unique_ips_recent_window{user="hello"} 76
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 189301.1 (52h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11879061
telemt_connections_bad_total 1234900
telemt_connections_current 539
telemt_connections_me_current 539
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 344577
telemt_upstream_connect_attempt_total 99211
telemt_upstream_connect_success_total 97885
telemt_upstream_connect_fail_total 873
telemt_upstream_connect_attempts_per_request{bucket="1"} 98758
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 52546
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 41350
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 188
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3801
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 873
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 225
telemt_me_reconnect_attempts_total 4432
telemt_me_reconnect_success_total 1882
telemt_me_reader_eof_total 1749
telemt_me_idle_close_by_peer_total 1749
telemt_me_route_drop_no_conn_total 4555853
telemt_me_route_drop_channel_closed_total 498
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8818606
telemt_me_endpoint_quarantine_total 1266
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1443
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
telemt_me_writers_active_current 44
telemt_desync_total 38789
telemt_desync_full_logged_total 13064
telemt_desync_suppressed_total 25725
telemt_desync_frames_bucket_total{bucket="1_2"} 9607
telemt_desync_frames_bucket_total{bucket="3_10"} 14900
telemt_desync_frames_bucket_total{bucket="gt_10"} 14282
telemt_pool_swap_total 202
telemt_pool_force_close_total 6079
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 711
telemt_me_draining_writers_reap_progress_total 62483
telemt_me_writer_removed_unexpected_total 1779
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5581
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 58537
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5567
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 512
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 56404
telemt_me_writer_teardown_success_total{mode="normal"} 64118
telemt_me_writer_teardown_noop_total 62508
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 119877
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 123102
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 124251
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 125442
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 126201
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 126541
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 126616
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 126618
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 126624
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 126626
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 126626
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 126626
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 126626
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 104.428553
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 126626
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 711
telemt_me_refill_failed_total 137
telemt_me_writer_restored_same_endpoint_total 1610
telemt_me_writer_restored_fallback_total 20
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 149
telemt_user_connections_total{user="hello"} 8756365
telemt_user_connections_current{user="hello"} 539
telemt_user_octets_from_client{user="hello"} 217795143120 (202.84 GB)
telemt_user_octets_to_client{user="hello"} 3963563983611 (3.60 TB)
telemt_user_msgs_from_client{user="hello"} 124042
telemt_user_msgs_to_client{user="hello"} 140191
telemt_user_unique_ips_current{user="hello"} 260
telemt_user_unique_ips_recent_window{user="hello"} 65
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 189265.1 (52h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11058303
telemt_connections_bad_total 975280
telemt_connections_current 498
telemt_connections_me_current 498
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 345578
telemt_upstream_connect_attempt_total 83466
telemt_upstream_connect_success_total 81907
telemt_upstream_connect_fail_total 205
telemt_upstream_connect_attempts_per_request{bucket="1"} 82112
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37762
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39754
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2029
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2362
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 205
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 1420
telemt_me_reconnect_attempts_total 5745
telemt_me_reconnect_success_total 2369
telemt_me_reader_eof_total 2114
telemt_me_idle_close_by_peer_total 2113
telemt_me_route_drop_no_conn_total 5337538
telemt_me_route_drop_channel_closed_total 383
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8358499
telemt_me_endpoint_quarantine_total 1332
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 38
telemt_me_single_endpoint_outage_reconnect_success_total 32
telemt_me_single_endpoint_quarantine_bypass_total 38
telemt_me_single_endpoint_shadow_rotate_total 1400
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 69
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
telemt_desync_total 38181
telemt_desync_full_logged_total 12640
telemt_desync_suppressed_total 25541
telemt_desync_frames_bucket_total{bucket="1_2"} 9642
telemt_desync_frames_bucket_total{bucket="3_10"} 14607
telemt_desync_frames_bucket_total{bucket="gt_10"} 13932
telemt_pool_swap_total 198
telemt_pool_force_close_total 5979
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 740
telemt_me_draining_writers_reap_progress_total 62841
telemt_me_writer_removed_unexpected_total 2264
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6326
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 58711
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5408
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 571
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 56862
telemt_me_writer_teardown_success_total{mode="normal"} 65037
telemt_me_writer_teardown_noop_total 62912
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 122116
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 124831
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 125794
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 126867
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 127468
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 127682
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 127810
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 127841
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 127849
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 127862
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 127895
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 127898
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 127949
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3174.786283
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 127949
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 740
telemt_me_refill_failed_total 179
telemt_me_writer_restored_same_endpoint_total 2059
telemt_me_writer_restored_fallback_total 17
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 188
telemt_user_connections_total{user="hello"} 8350458
telemt_user_connections_current{user="hello"} 498
telemt_user_octets_from_client{user="hello"} 192762217111 (179.52 GB)
telemt_user_octets_to_client{user="hello"} 3470748515365 (3.16 TB)
telemt_user_msgs_from_client{user="hello"} 46587
telemt_user_msgs_to_client{user="hello"} 113900
telemt_user_unique_ips_current{user="hello"} 206
telemt_user_unique_ips_recent_window{user="hello"} 54
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 59545.2 (16h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11244073
telemt_connections_bad_total 668668
telemt_connections_current 881
telemt_connections_me_current 881
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 272381
telemt_upstream_connect_attempt_total 57968
telemt_upstream_connect_success_total 54913
telemt_upstream_connect_fail_total 2028
telemt_upstream_connect_attempts_per_request{bucket="1"} 56941
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28424
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18956
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6016
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2028
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 7758
telemt_me_reconnect_success_total 1248
telemt_me_reader_eof_total 778
telemt_me_idle_close_by_peer_total 777
telemt_me_route_drop_no_conn_total 25290415
telemt_me_route_drop_channel_closed_total 59
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9331483
telemt_me_endpoint_quarantine_total 451
telemt_me_single_endpoint_outage_enter_total 94
telemt_me_single_endpoint_outage_exit_total 94
telemt_me_single_endpoint_outage_reconnect_attempt_total 179
telemt_me_single_endpoint_outage_reconnect_success_total 47
telemt_me_single_endpoint_quarantine_bypass_total 179
telemt_me_single_endpoint_shadow_rotate_total 476
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
telemt_desync_total 16335
telemt_desync_full_logged_total 4455
telemt_desync_suppressed_total 11880
telemt_desync_frames_bucket_total{bucket="1_2"} 3093
telemt_desync_frames_bucket_total{bucket="3_10"} 6653
telemt_desync_frames_bucket_total{bucket="gt_10"} 6589
telemt_pool_swap_total 62
telemt_pool_force_close_total 1999
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 484
telemt_me_draining_writers_reap_progress_total 18611
telemt_me_writer_removed_unexpected_total 1135
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2533
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17156
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1692
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 307
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16612
telemt_me_writer_teardown_success_total{mode="normal"} 19689
telemt_me_writer_teardown_noop_total 18630
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 34406
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 36175
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 36898
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 37774
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 38140
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 38263
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 38319
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 38319
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 38319
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 38319
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 38319
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 38319
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 38319
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 53.739892
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 38319
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 484
telemt_me_refill_failed_total 339
telemt_me_writer_restored_same_endpoint_total 800
telemt_me_writer_restored_fallback_total 11
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3149
telemt_me_writer_removed_unexpected_minus_restored_total 324
telemt_user_connections_total{user="hello"} 9357364
telemt_user_connections_current{user="hello"} 881
telemt_user_octets_from_client{user="hello"} 87271773306 (81.28 GB)
telemt_user_octets_to_client{user="hello"} 608379944682 (566.60 GB)
telemt_user_msgs_from_client{user="hello"} 68321
telemt_user_msgs_to_client{user="hello"} 57932
telemt_user_unique_ips_current{user="hello"} 396
telemt_user_unique_ips_recent_window{user="hello"} 91
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 189271.8 (52h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10993834
telemt_connections_bad_total 947011
telemt_connections_current 515
telemt_connections_me_current 515
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 242225
telemt_upstream_connect_attempt_total 112371
telemt_upstream_connect_success_total 111211
telemt_upstream_connect_fail_total 987
telemt_upstream_connect_attempts_per_request{bucket="1"} 112198
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 66278
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 43333
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1362
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 987
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 72939
telemt_me_reconnect_success_total 3081
telemt_me_reader_eof_total 2769
telemt_me_idle_close_by_peer_total 2767
telemt_me_route_drop_no_conn_total 5262726
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8676727
telemt_me_endpoint_quarantine_total 1278
telemt_me_single_endpoint_outage_enter_total 43
telemt_me_single_endpoint_outage_exit_total 43
telemt_me_single_endpoint_outage_reconnect_attempt_total 45
telemt_me_single_endpoint_outage_reconnect_success_total 43
telemt_me_single_endpoint_quarantine_bypass_total 45
telemt_me_single_endpoint_shadow_rotate_total 1431
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
telemt_me_writers_active_current 44
telemt_desync_total 46233
telemt_desync_full_logged_total 15832
telemt_desync_suppressed_total 30401
telemt_desync_frames_bucket_total{bucket="1_2"} 9395
telemt_desync_frames_bucket_total{bucket="3_10"} 17700
telemt_desync_frames_bucket_total{bucket="gt_10"} 19138
telemt_pool_swap_total 194
telemt_pool_force_close_total 5692
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 664
telemt_me_draining_writers_reap_progress_total 67010
telemt_me_writer_removed_unexpected_total 2797
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6850
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 62993
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4943
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 749
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 61318
telemt_me_writer_teardown_success_total{mode="normal"} 69843
telemt_me_writer_teardown_noop_total 67011
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 134705
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 136118
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 136537
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 136810
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 136844
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 136847
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 136847
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 136850
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 136854
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 136854
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 136854
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 136854
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 136854
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.267697
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 136854
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 664
telemt_me_refill_failed_total 4300
telemt_me_writer_restored_same_endpoint_total 2597
telemt_me_writer_restored_fallback_total 52
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7367
telemt_me_writer_removed_unexpected_minus_restored_total 148
telemt_user_connections_total{user="hello"} 8679705
telemt_user_connections_current{user="hello"} 515
telemt_user_octets_from_client{user="hello"} 194602583985 (181.24 GB)
telemt_user_octets_to_client{user="hello"} 3317533174116 (3.02 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 241
telemt_user_unique_ips_recent_window{user="hello"} 64
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 126108.1 (35h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11700116
telemt_connections_bad_total 482386
telemt_connections_current 654
telemt_connections_me_current 654
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4761990
telemt_upstream_connect_attempt_total 60678
telemt_upstream_connect_success_total 60234
telemt_upstream_connect_fail_total 433
telemt_upstream_connect_attempts_per_request{bucket="1"} 60667
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32242
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27774
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 218
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 433
telemt_me_reconnect_attempts_total 48961
telemt_me_reconnect_success_total 1815
telemt_me_reader_eof_total 1487
telemt_me_idle_close_by_peer_total 1486
telemt_me_route_drop_no_conn_total 4093314
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5621405
telemt_me_endpoint_quarantine_total 850
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 965
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
telemt_me_writers_active_current 44
telemt_me_writers_warm_current 41
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 31611
telemt_desync_full_logged_total 10784
telemt_desync_suppressed_total 20827
telemt_desync_frames_bucket_total{bucket="1_2"} 6293
telemt_desync_frames_bucket_total{bucket="3_10"} 12469
telemt_desync_frames_bucket_total{bucket="gt_10"} 12849
telemt_pool_swap_total 134
telemt_pool_force_close_total 3892
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 375
telemt_me_draining_writers_reap_progress_total 46200
telemt_me_writer_removed_unexpected_total 1538
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3785
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 43996
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3451
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 441
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 42308
telemt_me_writer_teardown_success_total{mode="normal"} 47781
telemt_me_writer_teardown_noop_total 46207
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 92698
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 93451
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 93761
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 93988
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 93988
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 93988
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 93988
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 93988
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 93988
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 93988
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 93988
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 93988
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 93988
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.689535
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 93988
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 375
telemt_me_refill_failed_total 2739
telemt_me_writer_restored_same_endpoint_total 1609
telemt_me_writer_restored_fallback_total 26
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5613573
telemt_user_connections_current{user="hello"} 654
telemt_user_octets_from_client{user="hello"} 119111336088 (110.93 GB)
telemt_user_octets_to_client{user="hello"} 2178899081942 (1.98 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 326
telemt_user_unique_ips_recent_window{user="hello"} 58
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 107078.8 (29h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1523442
telemt_connections_bad_total 36726
telemt_connections_current 420
telemt_connections_me_current 420
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 30850
telemt_upstream_connect_attempt_total 50449
telemt_upstream_connect_success_total 50291
telemt_upstream_connect_fail_total 130
telemt_upstream_connect_attempts_per_request{bucket="1"} 50421
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23224
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26278
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 789
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 130
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2248
telemt_me_reconnect_success_total 912
telemt_me_reader_eof_total 899
telemt_me_idle_close_by_peer_total 899
telemt_me_route_drop_no_conn_total 517791
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1353925
telemt_me_endpoint_quarantine_total 882
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 884
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
telemt_me_writers_active_current 44
telemt_desync_total 9012
telemt_desync_full_logged_total 2626
telemt_desync_suppressed_total 6386
telemt_desync_frames_bucket_total{bucket="1_2"} 2532
telemt_desync_frames_bucket_total{bucket="3_10"} 3438
telemt_desync_frames_bucket_total{bucket="gt_10"} 3042
telemt_pool_swap_total 115
telemt_pool_force_close_total 2945
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 166
telemt_me_draining_writers_reap_progress_total 42667
telemt_me_writer_removed_unexpected_total 867
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3262
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 40311
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2857
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 39722
telemt_me_writer_teardown_success_total{mode="normal"} 43573
telemt_me_writer_teardown_noop_total 42671
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 85271
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 85977
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 86207
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 86244
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 86244
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 86244
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 86244
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 86244
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 86244
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 86244
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 86244
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 86244
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 86244
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.298752
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 86244
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 166
telemt_me_refill_failed_total 74
telemt_me_writer_restored_same_endpoint_total 776
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 70
telemt_user_connections_total{user="hello"} 1349740
telemt_user_connections_current{user="hello"} 420
telemt_user_octets_from_client{user="hello"} 25984426905 (24.20 GB)
telemt_user_octets_to_client{user="hello"} 575509505615 (535.98 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 187
telemt_user_unique_ips_recent_window{user="hello"} 53
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 189276.3 (52h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13325381
telemt_connections_bad_total 1600896
telemt_connections_current 591
telemt_connections_me_current 591
telemt_handshake_timeouts_total 388917
telemt_upstream_connect_attempt_total 74478
telemt_upstream_connect_success_total 74127
telemt_upstream_connect_fail_total 215
telemt_upstream_connect_attempts_per_request{bucket="1"} 74342
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36650
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37373
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 100
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 215
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2975
telemt_me_reconnect_success_total 1491
telemt_me_reader_eof_total 1475
telemt_me_idle_close_by_peer_total 1475
telemt_me_route_drop_no_conn_total 4483041
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 42
telemt_me_route_drop_queue_full_profile_total{profile="high"} 42
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10049169
telemt_me_endpoint_quarantine_total 1356
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1432
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
telemt_desync_total 42075
telemt_desync_full_logged_total 13743
telemt_desync_suppressed_total 28332
telemt_desync_frames_bucket_total{bucket="1_2"} 10174
telemt_desync_frames_bucket_total{bucket="3_10"} 15465
telemt_desync_frames_bucket_total{bucket="gt_10"} 16436
telemt_pool_swap_total 210
telemt_pool_force_close_total 5596
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 676
telemt_me_draining_writers_reap_progress_total 67313
telemt_me_writer_removed_unexpected_total 1413
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5318
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 63460
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5422
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 61717
telemt_me_writer_teardown_success_total{mode="normal"} 68778
telemt_me_writer_teardown_noop_total 67315
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 133478
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 135201
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 135584
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 135960
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 136080
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 136093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 136093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 136093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 136093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 136093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 136093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 136093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 136093
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.787966
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 136093
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 676
telemt_me_refill_failed_total 80
telemt_me_writer_restored_same_endpoint_total 1308
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 89
telemt_user_connections_total{user="hello"} 10015880
telemt_user_connections_current{user="hello"} 591
telemt_user_octets_from_client{user="hello"} 194803329904 (181.42 GB)
telemt_user_octets_to_client{user="hello"} 4439754859856 (4.04 TB)
telemt_user_unique_ips_current{user="hello"} 265
telemt_user_unique_ips_recent_window{user="hello"} 54
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 189273.0 (52h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11641767
telemt_connections_bad_total 1360098
telemt_connections_current 471
telemt_connections_me_current 471
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 311455
telemt_upstream_connect_attempt_total 101982
telemt_upstream_connect_success_total 101094
telemt_upstream_connect_fail_total 680
telemt_upstream_connect_attempts_per_request{bucket="1"} 101774
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 55153
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 42961
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2067
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 680
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 10477
telemt_me_reconnect_success_total 2585
telemt_me_reader_eof_total 2398
telemt_me_idle_close_by_peer_total 2397
telemt_me_seq_mismatch_total 97
telemt_me_route_drop_no_conn_total 5650535
telemt_me_route_drop_channel_closed_total 354
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8959550
telemt_me_endpoint_quarantine_total 1530
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 52
telemt_me_single_endpoint_outage_exit_total 52
telemt_me_single_endpoint_outage_reconnect_attempt_total 52
telemt_me_single_endpoint_outage_reconnect_success_total 50
telemt_me_single_endpoint_quarantine_bypass_total 52
telemt_me_single_endpoint_shadow_rotate_total 1434
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 57
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
telemt_desync_total 41807
telemt_desync_full_logged_total 13457
telemt_desync_suppressed_total 28350
telemt_desync_frames_bucket_total{bucket="1_2"} 10798
telemt_desync_frames_bucket_total{bucket="3_10"} 15379
telemt_desync_frames_bucket_total{bucket="gt_10"} 15630
telemt_pool_swap_total 200
telemt_pool_force_close_total 5376
telemt_pool_stale_pick_total 372
telemt_me_writer_close_signal_drop_total 664
telemt_me_draining_writers_reap_progress_total 67357
telemt_me_writer_removed_unexpected_total 2439
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6674
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 63207
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4905
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 61981
telemt_me_writer_teardown_success_total{mode="normal"} 69881
telemt_me_writer_teardown_noop_total 67362
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 134553
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 136335
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 136874
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 137193
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 137243
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 137243
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 137243
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 137243
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 137243
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 137243
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 137243
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 137243
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 137243
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.467521
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 137243
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 664
telemt_me_refill_failed_total 408
telemt_me_writer_restored_same_endpoint_total 2081
telemt_me_writer_restored_fallback_total 132
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 135
telemt_me_writer_removed_unexpected_minus_restored_total 226
telemt_user_connections_total{user="hello"} 8964137
telemt_user_connections_current{user="hello"} 471
telemt_user_octets_from_client{user="hello"} 157361737540 (146.55 GB)
telemt_user_octets_to_client{user="hello"} 3489661805398 (3.17 TB)
telemt_user_msgs_from_client{user="hello"} 103592
telemt_user_msgs_to_client{user="hello"} 254638
telemt_user_unique_ips_current{user="hello"} 229
telemt_user_unique_ips_recent_window{user="hello"} 52
```