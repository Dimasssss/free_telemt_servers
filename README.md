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

# Server Metrics 2026-03-17 07:40:53 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 46531.1 (12h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 308755
telemt_connections_bad_total 3537
telemt_handshake_timeouts_total 9770
telemt_upstream_connect_attempt_total 9565
telemt_upstream_connect_success_total 9514
telemt_upstream_connect_fail_total 51
telemt_upstream_connect_attempts_per_request{bucket="1"} 9565
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4363
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5145
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 51
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 7234
telemt_me_reconnect_success_total 7205
telemt_me_reader_eof_total 7670
telemt_me_idle_close_by_peer_total 7670
telemt_me_route_drop_no_conn_total 94379
telemt_me_route_drop_channel_closed_total 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 277567
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2129
telemt_desync_full_logged_total 618
telemt_desync_suppressed_total 1511
telemt_desync_frames_bucket_total{bucket="1_2"} 462
telemt_desync_frames_bucket_total{bucket="3_10"} 1060
telemt_desync_frames_bucket_total{bucket="gt_10"} 607
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 7278
telemt_me_writer_restored_same_endpoint_total 7184
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 73
telemt_user_connections_total{user="hello"} 277336
telemt_user_connections_current{user="hello"} 813
telemt_user_octets_from_client{user="hello"} 3779923604 (3.52 GB)
telemt_user_octets_to_client{user="hello"} 120501054320 (112.23 GB)
telemt_user_unique_ips_current{user="hello"} 277
telemt_user_unique_ips_recent_window{user="hello"} 124
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 46783.0 (12h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 174376
telemt_connections_bad_total 2349
telemt_handshake_timeouts_total 11890
telemt_upstream_connect_attempt_total 12801
telemt_upstream_connect_success_total 12637
telemt_upstream_connect_fail_total 164
telemt_upstream_connect_attempts_per_request{bucket="1"} 12801
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5383
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7163
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 164
telemt_me_reconnect_attempts_total 11519
telemt_me_reconnect_success_total 10336
telemt_me_reader_eof_total 10909
telemt_me_idle_close_by_peer_total 10909
telemt_me_route_drop_no_conn_total 62731
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 150966
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 383
telemt_desync_full_logged_total 138
telemt_desync_suppressed_total 245
telemt_desync_frames_bucket_total{bucket="1_2"} 104
telemt_desync_frames_bucket_total{bucket="3_10"} 175
telemt_desync_frames_bucket_total{bucket="gt_10"} 104
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 10470
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 10320
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 134
telemt_user_connections_total{user="hello"} 150997
telemt_user_connections_current{user="hello"} 466
telemt_user_octets_from_client{user="hello"} 1840186940 (1.71 GB)
telemt_user_octets_to_client{user="hello"} 61672408700 (57.44 GB)
telemt_user_unique_ips_current{user="hello"} 151
telemt_user_unique_ips_recent_window{user="hello"} 66
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 46559.4 (12h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 105162
telemt_connections_bad_total 4061
telemt_handshake_timeouts_total 4707
telemt_upstream_connect_attempt_total 12195
telemt_upstream_connect_success_total 12132
telemt_upstream_connect_fail_total 63
telemt_upstream_connect_attempts_per_request{bucket="1"} 12195
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5350
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6720
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 63
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 9857
telemt_me_reconnect_success_total 9799
telemt_me_reader_eof_total 10492
telemt_me_idle_close_by_peer_total 10492
telemt_me_route_drop_no_conn_total 33438
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 87712
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 134
telemt_desync_full_logged_total 40
telemt_desync_suppressed_total 94
telemt_desync_frames_bucket_total{bucket="1_2"} 26
telemt_desync_frames_bucket_total{bucket="3_10"} 49
telemt_desync_frames_bucket_total{bucket="gt_10"} 59
telemt_pool_swap_total 45
telemt_me_writer_removed_unexpected_total 9921
telemt_me_writer_restored_same_endpoint_total 9788
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 122
telemt_user_connections_total{user="hello"} 87668
telemt_user_connections_current{user="hello"} 314
telemt_user_octets_from_client{user="hello"} 6391439860 (5.95 GB)
telemt_user_octets_to_client{user="hello"} 27151301448 (25.29 GB)
telemt_user_unique_ips_current{user="hello"} 99
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 46618.1 (12h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 204242
telemt_connections_bad_total 6050
telemt_handshake_timeouts_total 10000
telemt_upstream_connect_attempt_total 10695
telemt_upstream_connect_success_total 10604
telemt_upstream_connect_fail_total 91
telemt_upstream_connect_attempts_per_request{bucket="1"} 10695
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5010
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5526
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 91
telemt_me_keepalive_timeout_total 5
telemt_me_reconnect_attempts_total 8300
telemt_me_reconnect_success_total 8230
telemt_me_reader_eof_total 8731
telemt_me_idle_close_by_peer_total 8731
telemt_me_route_drop_no_conn_total 61231
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 172540
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 341
telemt_desync_full_logged_total 120
telemt_desync_suppressed_total 221
telemt_desync_frames_bucket_total{bucket="1_2"} 78
telemt_desync_frames_bucket_total{bucket="3_10"} 141
telemt_desync_frames_bucket_total{bucket="gt_10"} 122
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 8351
telemt_me_writer_restored_same_endpoint_total 8222
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 121
telemt_user_connections_total{user="hello"} 172546
telemt_user_connections_current{user="hello"} 557
telemt_user_octets_from_client{user="hello"} 1837819406 (1.71 GB)
telemt_user_octets_to_client{user="hello"} 77767043397 (72.43 GB)
telemt_user_msgs_from_client{user="hello"} 65
telemt_user_msgs_to_client{user="hello"} 189
telemt_user_unique_ips_current{user="hello"} 172
telemt_user_unique_ips_recent_window{user="hello"} 79
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 46590.0 (12h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 133794
telemt_connections_bad_total 38590
telemt_handshake_timeouts_total 2450
telemt_upstream_connect_attempt_total 14166
telemt_upstream_connect_success_total 13982
telemt_upstream_connect_fail_total 184
telemt_upstream_connect_attempts_per_request{bucket="1"} 14166
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6259
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7533
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 190
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 184
telemt_me_reconnect_attempts_total 14815
telemt_me_reconnect_success_total 11552
telemt_me_reader_eof_total 12197
telemt_me_idle_close_by_peer_total 12197
telemt_me_route_drop_no_conn_total 34882
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 88847
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 104
telemt_desync_full_logged_total 34
telemt_desync_suppressed_total 70
telemt_desync_frames_bucket_total{bucket="1_2"} 39
telemt_desync_frames_bucket_total{bucket="3_10"} 35
telemt_desync_frames_bucket_total{bucket="gt_10"} 30
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 11799
telemt_me_refill_failed_total 100
telemt_me_writer_restored_same_endpoint_total 11544
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 247
telemt_user_connections_total{user="hello"} 88888
telemt_user_connections_current{user="hello"} 208
telemt_user_octets_from_client{user="hello"} 929591599 (886.53 MB)
telemt_user_octets_to_client{user="hello"} 42027063806 (39.14 GB)
telemt_user_msgs_from_client{user="hello"} 265
telemt_user_msgs_to_client{user="hello"} 707
telemt_user_unique_ips_current{user="hello"} 76
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 46751.3 (12h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 316864
telemt_connections_bad_total 42166
telemt_handshake_timeouts_total 2809
telemt_upstream_connect_attempt_total 9674
telemt_upstream_connect_success_total 9624
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 9674
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4641
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4968
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_keepalive_timeout_total 16
telemt_me_reconnect_attempts_total 8562
telemt_me_reconnect_success_total 7311
telemt_me_reader_eof_total 7834
telemt_me_idle_close_by_peer_total 7834
telemt_me_route_drop_no_conn_total 238958
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 337703
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 358
telemt_desync_full_logged_total 160
telemt_desync_suppressed_total 198
telemt_desync_frames_bucket_total{bucket="1_2"} 123
telemt_desync_frames_bucket_total{bucket="3_10"} 129
telemt_desync_frames_bucket_total{bucket="gt_10"} 106
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 7455
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 7297
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 144
telemt_user_connections_total{user="hello"} 259634
telemt_user_connections_current{user="hello"} 708
telemt_user_octets_from_client{user="hello"} 3688756636 (3.44 GB)
telemt_user_octets_to_client{user="hello"} 163457103296 (152.23 GB)
telemt_user_unique_ips_current{user="hello"} 247
telemt_user_unique_ips_recent_window{user="hello"} 97
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 34757.6 (9h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1663
telemt_connections_bad_total 194
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 17309
telemt_upstream_connect_success_total 17308
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 17309
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9820
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7480
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 15592
telemt_me_reconnect_success_total 15503
telemt_me_reader_eof_total 16963
telemt_me_idle_close_by_peer_total 16963
telemt_me_route_drop_no_conn_total 254
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1452
telemt_me_writer_pick_total{mode="p2c",result="full"} 3
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 15641
telemt_me_writer_restored_same_endpoint_total 15503
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 138
telemt_user_connections_total{user="hello"} 1452
telemt_user_connections_current{user="hello"} 19
telemt_user_octets_from_client{user="hello"} 219488332 (209.32 MB)
telemt_user_octets_to_client{user="hello"} 16100730628 (14.99 GB)
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 2
```