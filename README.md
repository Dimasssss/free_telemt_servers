# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt  
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

**Принимаю донаты криптой для добавления и продления серверов:**  
- TON: UQAyIvWts4-gC0b5ouoy_JNDfBEe337c7oOBqpGXFB8fJUzB

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-60
- Краткое описание тарифа: 4 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 19 апреля
- Ссылка:
```bash
tg://proxy?server=s1.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## psb.hosting
- Локация: Finland
- Тариф: FI-200
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 12$
- Оплачен до: 25 марта
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

## rdp-onedash.ru
- Локация: Нидерланды
- Тариф: Mini
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 844 RUB
- Оплачен до: 14 апреля
- Ссылка:
```bash
tg://proxy?server=s5.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## hostvds.com
- Локация: Нидерланды, Амстердам
- Тариф: Burstable
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 10 Gbit/s
- Цена в месяц: €7.98
- Оплачен до: 13 апреля
- Ссылка:
```bash
tg://proxy?server=s6.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## 4vps.su
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

# Server Metrics 2026-03-20 06:55:20 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 49064.7 (13h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 999686
telemt_connections_bad_total 61341
telemt_connections_current 1609
telemt_connections_me_current 1609
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 26260
telemt_upstream_connect_attempt_total 9471
telemt_upstream_connect_success_total 9365
telemt_upstream_connect_fail_total 106
telemt_upstream_connect_attempts_per_request{bucket="1"} 9471
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5114
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4221
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 106
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 5857
telemt_me_reconnect_success_total 5813
telemt_me_reader_eof_total 6158
telemt_me_idle_close_by_peer_total 6157
telemt_me_route_drop_no_conn_total 287463
telemt_me_route_drop_channel_closed_total 108
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 816568
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4228
telemt_desync_full_logged_total 1530
telemt_desync_suppressed_total 2698
telemt_desync_frames_bucket_total{bucket="1_2"} 835
telemt_desync_frames_bucket_total{bucket="3_10"} 1640
telemt_desync_frames_bucket_total{bucket="gt_10"} 1753
telemt_pool_swap_total 53
telemt_me_writer_close_signal_drop_total 51
telemt_me_writer_removed_unexpected_total 5876
telemt_me_writer_restored_same_endpoint_total 5800
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 20
telemt_me_async_recovery_trigger_total 447
telemt_me_writer_removed_unexpected_minus_restored_total 63
telemt_user_connections_total{user="hello"} 815964
telemt_user_connections_current{user="hello"} 1609
telemt_user_octets_from_client{user="hello"} 34523009448 (32.15 GB)
telemt_user_octets_to_client{user="hello"} 280975182177 (261.68 GB)
telemt_user_msgs_from_client{user="hello"} 2449
telemt_user_msgs_to_client{user="hello"} 3730
telemt_user_unique_ips_current{user="hello"} 581
telemt_user_unique_ips_recent_window{user="hello"} 204
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 65520.3 (18h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4434219
telemt_connections_bad_total 419439
telemt_connections_current 5393
telemt_connections_me_current 5393
telemt_handshake_timeouts_total 99199
telemt_upstream_connect_attempt_total 12237
telemt_upstream_connect_success_total 12012
telemt_upstream_connect_fail_total 225
telemt_upstream_connect_attempts_per_request{bucket="1"} 12237
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6765
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5184
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 63
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 225
telemt_me_keepalive_timeout_total 56
telemt_me_reconnect_attempts_total 11800
telemt_me_reconnect_success_total 7543
telemt_me_reader_eof_total 8070
telemt_me_idle_close_by_peer_total 8069
telemt_me_route_drop_no_conn_total 2127102
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3621240
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 14160
telemt_desync_full_logged_total 4713
telemt_desync_suppressed_total 9447
telemt_desync_frames_bucket_total{bucket="1_2"} 2824
telemt_desync_frames_bucket_total{bucket="3_10"} 5511
telemt_desync_frames_bucket_total{bucket="gt_10"} 5825
telemt_pool_swap_total 58
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 73
telemt_me_writer_removed_unexpected_total 7776
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 7488
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 233
telemt_user_connections_total{user="hello"} 3620888
telemt_user_connections_current{user="hello"} 5393
telemt_user_octets_from_client{user="hello"} 52067163854 (48.49 GB)
telemt_user_octets_to_client{user="hello"} 1320392637458 (1.20 TB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1757
telemt_user_unique_ips_recent_window{user="hello"} 718
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 65498.6 (18h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4036303
telemt_connections_bad_total 522318
telemt_connections_current 3438
telemt_connections_me_current 3438
telemt_handshake_timeouts_total 63407
telemt_upstream_connect_attempt_total 12094
telemt_upstream_connect_success_total 11990
telemt_upstream_connect_fail_total 104
telemt_upstream_connect_attempts_per_request{bucket="1"} 12094
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6230
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5534
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 215
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 104
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 3075
telemt_me_reconnect_attempts_total 8238
telemt_me_reconnect_success_total 7278
telemt_me_reader_eof_total 7605
telemt_me_idle_close_by_peer_total 7600
telemt_me_route_drop_no_conn_total 2720761
telemt_me_route_drop_channel_closed_total 250
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2897228
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 179
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9988
telemt_desync_full_logged_total 3127
telemt_desync_suppressed_total 6861
telemt_desync_frames_bucket_total{bucket="1_2"} 2461
telemt_desync_frames_bucket_total{bucket="3_10"} 3832
telemt_desync_frames_bucket_total{bucket="gt_10"} 3695
telemt_pool_swap_total 64
telemt_me_writer_close_signal_drop_total 311
telemt_me_writer_removed_unexpected_total 7372
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 7277
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 94
telemt_user_connections_total{user="hello"} 2903620
telemt_user_connections_current{user="hello"} 3438
telemt_user_octets_from_client{user="hello"} 40497536042 (37.72 GB)
telemt_user_octets_to_client{user="hello"} 1084907858124 (1010.40 GB)
telemt_user_msgs_from_client{user="hello"} 2664
telemt_user_msgs_to_client{user="hello"} 1842
telemt_user_unique_ips_current{user="hello"} 1186
telemt_user_unique_ips_recent_window{user="hello"} 507
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 65486.1 (18h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4189510
telemt_connections_bad_total 277307
telemt_connections_current 5362
telemt_connections_me_current 5362
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1790
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 59928
telemt_upstream_connect_attempt_total 67878
telemt_upstream_connect_success_total 63144
telemt_upstream_connect_fail_total 4734
telemt_upstream_connect_attempts_per_request{bucket="1"} 67878
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 52615
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9792
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 712
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4734
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 10483
telemt_me_reconnect_success_total 7500
telemt_me_reader_eof_total 7833
telemt_me_idle_close_by_peer_total 7832
telemt_me_route_drop_no_conn_total 4303257
telemt_me_route_drop_channel_closed_total 76
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3485686
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11980
telemt_desync_full_logged_total 3569
telemt_desync_suppressed_total 8411
telemt_desync_frames_bucket_total{bucket="1_2"} 2793
telemt_desync_frames_bucket_total{bucket="3_10"} 4656
telemt_desync_frames_bucket_total{bucket="gt_10"} 4531
telemt_pool_swap_total 53
telemt_me_writer_close_signal_drop_total 676
telemt_me_writer_removed_unexpected_total 8226
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 7496
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 410
telemt_me_writer_removed_unexpected_minus_restored_total 726
telemt_user_connections_total{user="hello"} 3536766
telemt_user_connections_current{user="hello"} 5362
telemt_user_octets_from_client{user="hello"} 44896967836 (41.81 GB)
telemt_user_octets_to_client{user="hello"} 838201227899 (780.64 GB)
telemt_user_msgs_from_client{user="hello"} 260491
telemt_user_msgs_to_client{user="hello"} 1782062
telemt_user_unique_ips_current{user="hello"} 1417
telemt_user_unique_ips_recent_window{user="hello"} 813
```

## rdp-onedash.ru

```
telemt 3.3.24

telemt_uptime_seconds 3069.2 (0h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 418546
telemt_connections_bad_total 46786
telemt_connections_current 4996
telemt_connections_me_current 4996
telemt_handshake_timeouts_total 8527
telemt_upstream_connect_attempt_total 520
telemt_upstream_connect_success_total 517
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 520
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 286
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 230
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 316
telemt_me_reconnect_success_total 314
telemt_me_reader_eof_total 292
telemt_me_idle_close_by_peer_total 292
telemt_me_route_drop_no_conn_total 363526
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 335399
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 933
telemt_desync_full_logged_total 300
telemt_desync_suppressed_total 633
telemt_desync_frames_bucket_total{bucket="1_2"} 160
telemt_desync_frames_bucket_total{bucket="3_10"} 395
telemt_desync_frames_bucket_total{bucket="gt_10"} 378
telemt_pool_swap_total 2
telemt_me_writer_close_signal_drop_total 22
telemt_me_writer_removed_unexpected_total 304
telemt_me_writer_restored_same_endpoint_total 284
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 156
telemt_user_connections_total{user="hello"} 335330
telemt_user_connections_current{user="hello"} 4996
telemt_user_octets_from_client{user="hello"} 6050656384 (5.64 GB)
telemt_user_octets_to_client{user="hello"} 78515631912 (73.12 GB)
telemt_user_unique_ips_current{user="hello"} 1522
telemt_user_unique_ips_recent_window{user="hello"} 877
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 3004.4 (0h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 46879
telemt_connections_bad_total 8771
telemt_connections_current 650
telemt_connections_me_current 650
telemt_handshake_timeouts_total 480
telemt_upstream_connect_attempt_total 603
telemt_upstream_connect_success_total 596
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 603
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 308
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 287
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_reconnect_attempts_total 396
telemt_me_reconnect_success_total 394
telemt_me_reader_eof_total 388
telemt_me_idle_close_by_peer_total 388
telemt_me_route_drop_no_conn_total 28842
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 48440
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 181
telemt_desync_full_logged_total 57
telemt_desync_suppressed_total 124
telemt_desync_frames_bucket_total{bucket="1_2"} 23
telemt_desync_frames_bucket_total{bucket="3_10"} 79
telemt_desync_frames_bucket_total{bucket="gt_10"} 79
telemt_pool_swap_total 2
telemt_me_writer_close_signal_drop_total 23
telemt_me_writer_removed_unexpected_total 395
telemt_me_writer_restored_same_endpoint_total 386
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 198
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 35947
telemt_user_connections_current{user="hello"} 650
telemt_user_octets_from_client{user="hello"} 313596244 (299.07 MB)
telemt_user_octets_to_client{user="hello"} 13891503872 (12.94 GB)
telemt_user_unique_ips_current{user="hello"} 226
telemt_user_unique_ips_recent_window{user="hello"} 97
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 65450.7 (18h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2842841
telemt_connections_bad_total 182196
telemt_connections_current 4437
telemt_connections_me_current 4437
telemt_handshake_timeouts_total 51451
telemt_upstream_connect_attempt_total 11568
telemt_upstream_connect_success_total 11496
telemt_upstream_connect_fail_total 72
telemt_upstream_connect_attempts_per_request{bucket="1"} 11568
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6221
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 72
telemt_me_keepalive_timeout_total 14
telemt_me_reconnect_attempts_total 8306
telemt_me_reconnect_success_total 8252
telemt_me_reader_eof_total 8726
telemt_me_idle_close_by_peer_total 8726
telemt_me_route_drop_no_conn_total 967018
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2382007
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11916
telemt_desync_full_logged_total 3898
telemt_desync_suppressed_total 8018
telemt_desync_frames_bucket_total{bucket="1_2"} 2391
telemt_desync_frames_bucket_total{bucket="3_10"} 4189
telemt_desync_frames_bucket_total{bucket="gt_10"} 5336
telemt_pool_swap_total 67
telemt_me_writer_close_signal_drop_total 45
telemt_me_writer_removed_unexpected_total 8366
telemt_me_writer_restored_same_endpoint_total 8235
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 114
telemt_user_connections_total{user="hello"} 2380891
telemt_user_connections_current{user="hello"} 4437
telemt_user_octets_from_client{user="hello"} 52404041996 (48.81 GB)
telemt_user_octets_to_client{user="hello"} 1247390786080 (1.13 TB)
telemt_user_unique_ips_current{user="hello"} 1370
telemt_user_unique_ips_recent_window{user="hello"} 555
```