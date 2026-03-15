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

# Server Metrics 2026-03-15 18:27:43 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 72794.2 (20h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 341885
telemt_connections_bad_total 4198
telemt_handshake_timeouts_total 11052
telemt_upstream_connect_attempt_total 17609
telemt_upstream_connect_success_total 17521
telemt_upstream_connect_fail_total 88
telemt_upstream_connect_attempts_per_request{bucket="1"} 17609
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7762
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9722
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 88
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 32
telemt_me_reconnect_attempts_total 17297
telemt_me_reconnect_success_total 13898
telemt_me_reader_eof_total 14803
telemt_me_idle_close_by_peer_total 14803
telemt_me_route_drop_no_conn_total 464637
telemt_me_route_drop_channel_closed_total 76
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 374507
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1886
telemt_desync_full_logged_total 747
telemt_desync_suppressed_total 1139
telemt_desync_frames_bucket_total{bucket="1_2"} 358
telemt_desync_frames_bucket_total{bucket="3_10"} 733
telemt_desync_frames_bucket_total{bucket="gt_10"} 795
telemt_pool_swap_total 64
telemt_me_writer_removed_unexpected_total 14155
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 13864
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 257
telemt_user_connections_total{user="hello"} 313608
telemt_user_connections_current{user="hello"} 345
telemt_user_octets_from_client{user="hello"} 6417966936 (5.98 GB)
telemt_user_octets_to_client{user="hello"} 244627232576 (227.83 GB)
telemt_user_unique_ips_current{user="hello"} 112
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 72800.9 (20h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 137149
telemt_connections_bad_total 2835
telemt_handshake_timeouts_total 12396
telemt_upstream_connect_attempt_total 19670
telemt_upstream_connect_success_total 19670
telemt_upstream_connect_attempts_per_request{bucket="1"} 19670
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8384
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10961
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 325
telemt_me_keepalive_timeout_total 44
telemt_me_reconnect_attempts_total 18373
telemt_me_reconnect_success_total 16006
telemt_me_reader_eof_total 17111
telemt_me_idle_close_by_peer_total 17110
telemt_me_route_drop_no_conn_total 56946
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 116323
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3
telemt_desync_full_logged_total 3
telemt_desync_frames_bucket_total{bucket="1_2"} 1
telemt_desync_frames_bucket_total{bucket="3_10"} 2
telemt_pool_swap_total 63
telemt_me_writer_removed_unexpected_total 16292
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 15990
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 286
telemt_user_connections_total{user="hello"} 116303
telemt_user_connections_current{user="hello"} 191
telemt_user_octets_from_client{user="hello"} 2190200380 (2.04 GB)
telemt_user_octets_to_client{user="hello"} 58319882448 (54.31 GB)
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 72793.0 (20h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 140981
telemt_connections_bad_total 1700
telemt_handshake_timeouts_total 3292
telemt_upstream_connect_attempt_total 21211
telemt_upstream_connect_success_total 21203
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 21211
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9202
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11965
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 35
telemt_me_reconnect_attempts_total 24884
telemt_me_reconnect_success_total 17525
telemt_me_reader_eof_total 18809
telemt_me_idle_close_by_peer_total 18809
telemt_me_route_drop_no_conn_total 55215
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 124127
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 59
telemt_desync_full_logged_total 23
telemt_desync_suppressed_total 36
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 29
telemt_desync_frames_bucket_total{bucket="gt_10"} 25
telemt_pool_swap_total 59
telemt_me_writer_removed_unexpected_total 17923
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 17517
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 398
telemt_user_connections_total{user="hello"} 124019
telemt_user_connections_current{user="hello"} 154
telemt_user_octets_from_client{user="hello"} 10753784980 (10.02 GB)
telemt_user_octets_to_client{user="hello"} 68953635504 (64.22 GB)
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 72792.7 (20h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 194779
telemt_connections_bad_total 963
telemt_handshake_timeouts_total 1314
telemt_upstream_connect_attempt_total 17201
telemt_upstream_connect_success_total 17188
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 17201
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8226
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8892
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 67
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_timeout_total 20
telemt_me_reconnect_attempts_total 13651
telemt_me_reconnect_success_total 13568
telemt_me_reader_eof_total 14438
telemt_me_idle_close_by_peer_total 14438
telemt_me_route_drop_no_conn_total 73562
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 179593
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 639
telemt_desync_full_logged_total 239
telemt_desync_suppressed_total 400
telemt_desync_frames_bucket_total{bucket="1_2"} 134
telemt_desync_frames_bucket_total{bucket="3_10"} 299
telemt_desync_frames_bucket_total{bucket="gt_10"} 206
telemt_pool_swap_total 66
telemt_me_writer_removed_unexpected_total 13731
telemt_me_writer_restored_same_endpoint_total 13557
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 163
telemt_user_connections_total{user="hello"} 179505
telemt_user_connections_current{user="hello"} 271
telemt_user_octets_from_client{user="hello"} 3312659256 (3.09 GB)
telemt_user_octets_to_client{user="hello"} 83701086952 (77.95 GB)
telemt_user_unique_ips_current{user="hello"} 84
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 47864.2 (13h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 117739
telemt_connections_bad_total 24112
telemt_handshake_timeouts_total 2465
telemt_upstream_connect_attempt_total 14212
telemt_upstream_connect_success_total 14128
telemt_upstream_connect_fail_total 84
telemt_upstream_connect_attempts_per_request{bucket="1"} 14212
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6484
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7570
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 74
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 84
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 105979
telemt_me_reconnect_success_total 11533
telemt_me_reader_eof_total 12118
telemt_me_idle_close_by_peer_total 12118
telemt_me_route_drop_no_conn_total 40393
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 87879
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 271
telemt_desync_full_logged_total 57
telemt_desync_suppressed_total 214
telemt_desync_frames_bucket_total{bucket="1_2"} 45
telemt_desync_frames_bucket_total{bucket="3_10"} 98
telemt_desync_frames_bucket_total{bucket="gt_10"} 128
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 11602
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 11429
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 69
telemt_user_connections_total{user="hello"} 88011
telemt_user_connections_current{user="hello"} 130
telemt_user_octets_from_client{user="hello"} 1472416985 (1.37 GB)
telemt_user_octets_to_client{user="hello"} 34221454679 (31.87 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 72792.3 (20h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 490538
telemt_connections_bad_total 57812
telemt_handshake_timeouts_total 4009
telemt_upstream_connect_attempt_total 15653
telemt_upstream_connect_success_total 15562
telemt_upstream_connect_fail_total 91
telemt_upstream_connect_attempts_per_request{bucket="1"} 15653
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7508
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8021
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 14
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 91
telemt_me_keepalive_timeout_total 62
telemt_me_reconnect_attempts_total 13218
telemt_me_reconnect_success_total 11913
telemt_me_reader_eof_total 12653
telemt_me_idle_close_by_peer_total 12653
telemt_me_route_drop_no_conn_total 314680
telemt_me_route_drop_channel_closed_total 76
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 452145
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 317
telemt_desync_full_logged_total 86
telemt_desync_suppressed_total 231
telemt_desync_frames_bucket_total{bucket="1_2"} 169
telemt_desync_frames_bucket_total{bucket="3_10"} 94
telemt_desync_frames_bucket_total{bucket="gt_10"} 54
telemt_pool_swap_total 61
telemt_me_writer_removed_unexpected_total 12079
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 11886
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 166
telemt_user_connections_total{user="hello"} 410722
telemt_user_connections_current{user="hello"} 525
telemt_user_octets_from_client{user="hello"} 10558445464 (9.83 GB)
telemt_user_octets_to_client{user="hello"} 224399614236 (208.99 GB)
telemt_user_unique_ips_current{user="hello"} 194
telemt_user_unique_ips_recent_window{user="hello"} 71
```