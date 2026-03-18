# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt  
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-40
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 26 марта
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

# Server Metrics 2026-03-18 14:31:29 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.20

telemt_uptime_seconds 21025.8 (5h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 780256
telemt_connections_bad_total 43814
telemt_handshake_timeouts_total 21368
telemt_upstream_connect_attempt_total 67031
telemt_upstream_connect_success_total 66065
telemt_upstream_connect_fail_total 966
telemt_upstream_connect_attempts_per_request{bucket="1"} 67031
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 60937
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4545
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 583
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 966
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 517146
telemt_me_reconnect_success_total 3003
telemt_me_reader_eof_total 3254
telemt_me_idle_close_by_peer_total 3252
telemt_me_route_drop_no_conn_total 438598
telemt_me_route_drop_channel_closed_total 170
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 604533
telemt_me_writer_pick_total{mode="p2c",result="full"} 21
telemt_me_writer_pick_total{mode="p2c",result="closed"} 54
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2657
telemt_desync_full_logged_total 930
telemt_desync_suppressed_total 1727
telemt_desync_frames_bucket_total{bucket="1_2"} 736
telemt_desync_frames_bucket_total{bucket="3_10"} 920
telemt_desync_frames_bucket_total{bucket="gt_10"} 1001
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 3258
telemt_me_refill_failed_total 16749
telemt_me_writer_restored_same_endpoint_total 2897
telemt_me_writer_restored_fallback_total 106
telemt_me_async_recovery_trigger_total 11769
telemt_me_writer_removed_unexpected_minus_restored_total 255
telemt_user_connections_total{user="hello"} 662636
telemt_user_connections_current{user="hello"} 1686
telemt_user_octets_from_client{user="hello"} 9707413316 (9.04 GB)
telemt_user_octets_to_client{user="hello"} 172994470369 (161.11 GB)
telemt_user_msgs_from_client{user="hello"} 846607
telemt_user_msgs_to_client{user="hello"} 1165163
telemt_user_unique_ips_current{user="hello"} 545
telemt_user_unique_ips_recent_window{user="hello"} 257
```

## psb.hosting

```
telemt 3.3.22

telemt_uptime_seconds 1594.2 (0h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 160686
telemt_connections_bad_total 8489
telemt_connections_current 4057
telemt_connections_me_current 4057
telemt_handshake_timeouts_total 3386
telemt_upstream_connect_attempt_total 293
telemt_upstream_connect_success_total 291
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 293
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 187
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 104
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 180
telemt_me_reconnect_success_total 177
telemt_me_reader_eof_total 71
telemt_me_idle_close_by_peer_total 71
telemt_me_route_drop_no_conn_total 76803
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 140227
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 430
telemt_desync_full_logged_total 138
telemt_desync_suppressed_total 292
telemt_desync_frames_bucket_total{bucket="1_2"} 104
telemt_desync_frames_bucket_total{bucket="3_10"} 164
telemt_desync_frames_bucket_total{bucket="gt_10"} 162
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 93
telemt_me_writer_restored_same_endpoint_total 175
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 2874
telemt_user_connections_total{user="hello"} 139982
telemt_user_connections_current{user="hello"} 4057
telemt_user_octets_from_client{user="hello"} 1729673812 (1.61 GB)
telemt_user_octets_to_client{user="hello"} 47580873600 (44.31 GB)
telemt_user_unique_ips_current{user="hello"} 1311
telemt_user_unique_ips_recent_window{user="hello"} 735
```

## koara.io

```
telemt 3.3.22

telemt_uptime_seconds 1522.5 (0h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 113449
telemt_connections_bad_total 5102
telemt_connections_current 3186
telemt_connections_me_current 3186
telemt_handshake_timeouts_total 2084
telemt_upstream_connect_attempt_total 210
telemt_upstream_connect_success_total 208
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 210
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 113
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 95
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 96
telemt_me_reconnect_success_total 95
telemt_me_reader_eof_total 78
telemt_me_idle_close_by_peer_total 78
telemt_me_route_drop_no_conn_total 35965
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 97642
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 307
telemt_desync_full_logged_total 89
telemt_desync_suppressed_total 218
telemt_desync_frames_bucket_total{bucket="1_2"} 41
telemt_desync_frames_bucket_total{bucket="3_10"} 111
telemt_desync_frames_bucket_total{bucket="gt_10"} 155
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 98
telemt_me_writer_restored_same_endpoint_total 78
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 652
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 97637
telemt_user_connections_current{user="hello"} 3186
telemt_user_octets_from_client{user="hello"} 2500642632 (2.33 GB)
telemt_user_octets_to_client{user="hello"} 37921837784 (35.32 GB)
telemt_user_unique_ips_current{user="hello"} 971
telemt_user_unique_ips_recent_window{user="hello"} 496
```

## landvps.ru

```
telemt 3.3.22

telemt_uptime_seconds 2237.6 (0h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 218474
telemt_connections_bad_total 876
telemt_connections_current 2863
telemt_connections_me_current 2863
telemt_handshake_timeouts_total 4343
telemt_upstream_connect_attempt_total 419
telemt_upstream_connect_success_total 417
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 419
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 212
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 202
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 258
telemt_me_reconnect_success_total 255
telemt_me_reader_eof_total 206
telemt_me_idle_close_by_peer_total 205
telemt_me_route_drop_no_conn_total 284165
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 193442
telemt_me_writer_pick_total{mode="p2c",result="full"} 30
telemt_me_writer_pick_total{mode="p2c",result="closed"} 61
telemt_me_endpoint_quarantine_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 595
telemt_desync_full_logged_total 170
telemt_desync_suppressed_total 425
telemt_desync_frames_bucket_total{bucket="1_2"} 123
telemt_desync_frames_bucket_total{bucket="3_10"} 279
telemt_desync_frames_bucket_total{bucket="gt_10"} 193
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 227
telemt_me_writer_restored_same_endpoint_total 244
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 1000
telemt_user_connections_total{user="hello"} 193414
telemt_user_connections_current{user="hello"} 2863
telemt_user_octets_from_client{user="hello"} 1197264240 (1.12 GB)
telemt_user_octets_to_client{user="hello"} 30084813704 (28.02 GB)
telemt_user_unique_ips_current{user="hello"} 887
telemt_user_unique_ips_recent_window{user="hello"} 471
```

## rdp-onedash.ru

```
telemt 3.3.20

telemt_uptime_seconds 20897.3 (5h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1731297
telemt_connections_bad_total 138152
telemt_handshake_timeouts_total 27790
telemt_upstream_connect_attempt_total 15233
telemt_upstream_connect_success_total 15205
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 15233
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12429
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1974
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 802
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_keepalive_timeout_total 70
telemt_me_reconnect_attempts_total 2986893
telemt_me_reconnect_success_total 2454
telemt_me_reader_eof_total 2567
telemt_me_idle_close_by_peer_total 2567
telemt_me_route_drop_no_conn_total 1850711
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1440215
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4019
telemt_desync_full_logged_total 1394
telemt_desync_suppressed_total 2625
telemt_desync_frames_bucket_total{bucket="1_2"} 666
telemt_desync_frames_bucket_total{bucket="3_10"} 1555
telemt_desync_frames_bucket_total{bucket="gt_10"} 1798
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 2524
telemt_me_refill_failed_total 107230
telemt_me_writer_restored_same_endpoint_total 2339
telemt_me_writer_restored_fallback_total 115
telemt_me_async_recovery_trigger_total 267383
telemt_me_writer_removed_unexpected_minus_restored_total 70
telemt_user_connections_total{user="hello"} 1442052
telemt_user_connections_current{user="hello"} 3060
telemt_user_octets_from_client{user="hello"} 21472362539 (20.00 GB)
telemt_user_octets_to_client{user="hello"} 474877770933 (442.26 GB)
telemt_user_msgs_from_client{user="hello"} 89703
telemt_user_msgs_to_client{user="hello"} 269409
telemt_user_unique_ips_current{user="hello"} 989
telemt_user_unique_ips_recent_window{user="hello"} 485
```

## hostvds.com

```
telemt 3.3.22

telemt_uptime_seconds 1688.6 (0h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 46779
telemt_connections_bad_total 3287
telemt_connections_current 957
telemt_connections_me_current 957
telemt_relay_adaptive_promotions_total 18
telemt_relay_adaptive_hard_promotions_total 18
telemt_handshake_timeouts_total 417
telemt_upstream_connect_attempt_total 4328
telemt_upstream_connect_success_total 4325
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 4328
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2592
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1706
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 22
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 329844
telemt_me_reconnect_success_total 391
telemt_me_reader_eof_total 287
telemt_me_idle_close_by_peer_total 287
telemt_me_route_drop_no_conn_total 31303
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 37070
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 9
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 91
telemt_desync_full_logged_total 25
telemt_desync_suppressed_total 66
telemt_desync_frames_bucket_total{bucket="1_2"} 21
telemt_desync_frames_bucket_total{bucket="3_10"} 37
telemt_desync_frames_bucket_total{bucket="gt_10"} 33
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 304
telemt_me_refill_failed_total 10448
telemt_me_writer_restored_same_endpoint_total 380
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 40876
telemt_user_connections_total{user="hello"} 40847
telemt_user_connections_current{user="hello"} 957
telemt_user_octets_from_client{user="hello"} 630916757 (601.69 MB)
telemt_user_octets_to_client{user="hello"} 5513603981 (5.13 GB)
telemt_user_msgs_from_client{user="hello"} 38712
telemt_user_msgs_to_client{user="hello"} 31668
telemt_user_unique_ips_current{user="hello"} 329
telemt_user_unique_ips_recent_window{user="hello"} 168
```

## 4vps.su

```
telemt 3.3.22

telemt_uptime_seconds 756.1 (0h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 62403
telemt_connections_bad_total 464
telemt_connections_current 2670
telemt_connections_me_current 2670
telemt_handshake_timeouts_total 712
telemt_upstream_connect_attempt_total 251
telemt_upstream_connect_success_total 251
telemt_upstream_connect_attempts_per_request{bucket="1"} 251
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 169
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 82
telemt_me_reconnect_attempts_total 14467
telemt_me_reconnect_success_total 179
telemt_me_reader_eof_total 61
telemt_me_idle_close_by_peer_total 61
telemt_me_route_drop_no_conn_total 77624
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 57544
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 119
telemt_desync_full_logged_total 40
telemt_desync_suppressed_total 79
telemt_desync_frames_bucket_total{bucket="1_2"} 39
telemt_desync_frames_bucket_total{bucket="3_10"} 37
telemt_desync_frames_bucket_total{bucket="gt_10"} 43
telemt_me_writer_removed_unexpected_total 83
telemt_me_refill_failed_total 703
telemt_me_writer_restored_same_endpoint_total 118
telemt_me_writer_restored_fallback_total 61
telemt_me_async_recovery_trigger_total 9552
telemt_user_connections_total{user="hello"} 57541
telemt_user_connections_current{user="hello"} 2670
telemt_user_octets_from_client{user="hello"} 660244852 (629.66 MB)
telemt_user_octets_to_client{user="hello"} 10883279540 (10.14 GB)
telemt_user_unique_ips_current{user="hello"} 816
telemt_user_unique_ips_recent_window{user="hello"} 475
```