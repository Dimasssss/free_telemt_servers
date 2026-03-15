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

# Server Metrics 2026-03-15 17:36:40 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 69731.5 (19h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 325083
telemt_connections_bad_total 3595
telemt_handshake_timeouts_total 9300
telemt_upstream_connect_attempt_total 16999
telemt_upstream_connect_success_total 16912
telemt_upstream_connect_fail_total 87
telemt_upstream_connect_attempts_per_request{bucket="1"} 16999
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7480
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9398
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 87
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 32
telemt_me_reconnect_attempts_total 16817
telemt_me_reconnect_success_total 13422
telemt_me_reader_eof_total 14292
telemt_me_idle_close_by_peer_total 14292
telemt_me_route_drop_no_conn_total 460057
telemt_me_route_drop_channel_closed_total 76
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 360527
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1847
telemt_desync_full_logged_total 733
telemt_desync_suppressed_total 1114
telemt_desync_frames_bucket_total{bucket="1_2"} 340
telemt_desync_frames_bucket_total{bucket="3_10"} 726
telemt_desync_frames_bucket_total{bucket="gt_10"} 781
telemt_pool_swap_total 61
telemt_me_writer_removed_unexpected_total 13671
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 13388
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 249
telemt_user_connections_total{user="hello"} 299627
telemt_user_connections_current{user="hello"} 373
telemt_user_octets_from_client{user="hello"} 6154070516 (5.73 GB)
telemt_user_octets_to_client{user="hello"} 238281255008 (221.92 GB)
telemt_user_unique_ips_current{user="hello"} 123
telemt_user_unique_ips_recent_window{user="hello"} 51
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 69738.9 (19h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 129517
telemt_connections_bad_total 2829
telemt_handshake_timeouts_total 11827
telemt_upstream_connect_attempt_total 19023
telemt_upstream_connect_success_total 19023
telemt_upstream_connect_attempts_per_request{bucket="1"} 19023
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8147
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10598
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 278
telemt_me_keepalive_timeout_total 44
telemt_me_reconnect_attempts_total 17855
telemt_me_reconnect_success_total 15492
telemt_me_reader_eof_total 16562
telemt_me_idle_close_by_peer_total 16561
telemt_me_route_drop_no_conn_total 53945
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 109915
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
telemt_pool_swap_total 60
telemt_me_writer_removed_unexpected_total 15763
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 15476
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 271
telemt_user_connections_total{user="hello"} 109897
telemt_user_connections_current{user="hello"} 181
telemt_user_octets_from_client{user="hello"} 2091934580 (1.95 GB)
telemt_user_octets_to_client{user="hello"} 53959638020 (50.25 GB)
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 69731.5 (19h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 133862
telemt_connections_bad_total 1696
telemt_handshake_timeouts_total 3253
telemt_upstream_connect_attempt_total 20546
telemt_upstream_connect_success_total 20538
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 20546
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8904
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11598
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 35
telemt_me_reconnect_attempts_total 24348
telemt_me_reconnect_success_total 16992
telemt_me_reader_eof_total 18236
telemt_me_idle_close_by_peer_total 18236
telemt_me_route_drop_no_conn_total 52331
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 117403
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
telemt_pool_swap_total 56
telemt_me_writer_removed_unexpected_total 17383
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 16984
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 391
telemt_user_connections_total{user="hello"} 117296
telemt_user_connections_current{user="hello"} 171
telemt_user_octets_from_client{user="hello"} 10666954756 (9.93 GB)
telemt_user_octets_to_client{user="hello"} 66859932512 (62.27 GB)
telemt_user_unique_ips_current{user="hello"} 67
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 69730.9 (19h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 181842
telemt_connections_bad_total 928
telemt_handshake_timeouts_total 1195
telemt_upstream_connect_attempt_total 16618
telemt_upstream_connect_success_total 16606
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 16618
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7969
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8570
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 20
telemt_me_reconnect_attempts_total 13198
telemt_me_reconnect_success_total 13117
telemt_me_reader_eof_total 13960
telemt_me_idle_close_by_peer_total 13960
telemt_me_route_drop_no_conn_total 69949
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 167756
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 582
telemt_desync_full_logged_total 211
telemt_desync_suppressed_total 371
telemt_desync_frames_bucket_total{bucket="1_2"} 120
telemt_desync_frames_bucket_total{bucket="3_10"} 268
telemt_desync_frames_bucket_total{bucket="gt_10"} 194
telemt_pool_swap_total 63
telemt_me_writer_removed_unexpected_total 13277
telemt_me_writer_restored_same_endpoint_total 13106
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 160
telemt_user_connections_total{user="hello"} 167668
telemt_user_connections_current{user="hello"} 297
telemt_user_octets_from_client{user="hello"} 3130657436 (2.92 GB)
telemt_user_octets_to_client{user="hello"} 74696186456 (69.57 GB)
telemt_user_unique_ips_current{user="hello"} 81
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 44802.3 (12h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 110669
telemt_connections_bad_total 23537
telemt_handshake_timeouts_total 2435
telemt_upstream_connect_attempt_total 13538
telemt_upstream_connect_success_total 13461
telemt_upstream_connect_fail_total 77
telemt_upstream_connect_attempts_per_request{bucket="1"} 13538
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6163
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7224
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 74
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 77
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 105485
telemt_me_reconnect_success_total 11042
telemt_me_reader_eof_total 11589
telemt_me_idle_close_by_peer_total 11589
telemt_me_route_drop_no_conn_total 37969
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 81745
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 194
telemt_desync_full_logged_total 47
telemt_desync_suppressed_total 147
telemt_desync_frames_bucket_total{bucket="1_2"} 35
telemt_desync_frames_bucket_total{bucket="3_10"} 76
telemt_desync_frames_bucket_total{bucket="gt_10"} 83
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 11104
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 10938
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 62
telemt_user_connections_total{user="hello"} 81878
telemt_user_connections_current{user="hello"} 140
telemt_user_octets_from_client{user="hello"} 1381469169 (1.29 GB)
telemt_user_octets_to_client{user="hello"} 32056120307 (29.85 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 69730.7 (19h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 463825
telemt_connections_bad_total 57620
telemt_handshake_timeouts_total 3789
telemt_upstream_connect_attempt_total 15106
telemt_upstream_connect_success_total 15015
telemt_upstream_connect_fail_total 91
telemt_upstream_connect_attempts_per_request{bucket="1"} 15106
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7295
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7692
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 91
telemt_me_keepalive_timeout_total 62
telemt_me_reconnect_attempts_total 12800
telemt_me_reconnect_success_total 11496
telemt_me_reader_eof_total 12209
telemt_me_idle_close_by_peer_total 12209
telemt_me_route_drop_no_conn_total 284571
telemt_me_route_drop_channel_closed_total 73
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 418884
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
telemt_pool_swap_total 58
telemt_me_writer_removed_unexpected_total 11659
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 11469
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 163
telemt_user_connections_total{user="hello"} 385374
telemt_user_connections_current{user="hello"} 619
telemt_user_octets_from_client{user="hello"} 10208736976 (9.51 GB)
telemt_user_octets_to_client{user="hello"} 205147360800 (191.06 GB)
telemt_user_unique_ips_current{user="hello"} 225
telemt_user_unique_ips_recent_window{user="hello"} 85
```