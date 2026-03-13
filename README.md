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

# Server Metrics 2026-03-13 06:11:32 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 81488.9 (22h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 308514
telemt_connections_bad_total 3086
telemt_handshake_timeouts_total 6309
telemt_upstream_connect_attempt_total 20565
telemt_upstream_connect_success_total 20468
telemt_upstream_connect_fail_total 97
telemt_upstream_connect_attempts_per_request{bucket="1"} 20565
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9216
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11204
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 97
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1613
telemt_me_reconnect_attempts_total 19873
telemt_me_reconnect_success_total 16373
telemt_me_reader_eof_total 17504
telemt_me_idle_close_by_peer_total 17503
telemt_me_route_drop_no_conn_total 96092
telemt_me_route_drop_channel_closed_total 16
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 260576
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 905
telemt_desync_full_logged_total 337
telemt_desync_suppressed_total 568
telemt_desync_frames_bucket_total{bucket="1_2"} 179
telemt_desync_frames_bucket_total{bucket="3_10"} 332
telemt_desync_frames_bucket_total{bucket="gt_10"} 394
telemt_pool_swap_total 73
telemt_me_writer_removed_unexpected_total 16659
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 16357
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 286
telemt_user_connections_total{user="hello"} 260513
telemt_user_connections_current{user="hello"} 293
telemt_user_octets_from_client{user="hello"} 4446101332 (4.14 GB)
telemt_user_octets_to_client{user="hello"} 125063671920 (116.47 GB)
telemt_user_unique_ips_current{user="hello"} 86
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 81382.5 (22h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 141489
telemt_connections_bad_total 1392
telemt_handshake_timeouts_total 1059
telemt_upstream_connect_attempt_total 42834
telemt_upstream_connect_success_total 42277
telemt_upstream_connect_fail_total 557
telemt_upstream_connect_attempts_per_request{bucket="1"} 42834
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25058
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16710
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 509
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 557
telemt_me_keepalive_timeout_total 620
telemt_me_reconnect_attempts_total 70891
telemt_me_reconnect_success_total 21702
telemt_me_reader_eof_total 23891
telemt_me_idle_close_by_peer_total 23891
telemt_me_route_drop_no_conn_total 53377
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 117397
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 32
telemt_desync_full_logged_total 10
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 18
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 23406
telemt_me_refill_failed_total 1535
telemt_me_writer_restored_same_endpoint_total 21687
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1704
telemt_user_connections_total{user="hello"} 133894
telemt_user_connections_current{user="hello"} 157
telemt_user_octets_from_client{user="hello"} 1390966352 (1.30 GB)
telemt_user_octets_to_client{user="hello"} 41544188095 (38.69 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 81345.9 (22h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 171158
telemt_connections_bad_total 1910
telemt_handshake_timeouts_total 2772
telemt_upstream_connect_attempt_total 22361
telemt_upstream_connect_success_total 22359
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 22361
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10295
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12041
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 496
telemt_me_reconnect_attempts_total 19415
telemt_me_reconnect_success_total 18244
telemt_me_reader_eof_total 19561
telemt_me_idle_close_by_peer_total 19561
telemt_me_route_drop_no_conn_total 66318
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 160091
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 62
telemt_desync_full_logged_total 30
telemt_desync_suppressed_total 32
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 20
telemt_desync_frames_bucket_total{bucket="gt_10"} 39
telemt_pool_swap_total 74
telemt_me_writer_removed_unexpected_total 18444
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 18224
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 200
telemt_user_connections_total{user="hello"} 160019
telemt_user_connections_current{user="hello"} 116
telemt_user_octets_from_client{user="hello"} 2942573196 (2.74 GB)
telemt_user_octets_to_client{user="hello"} 72597094492 (67.61 GB)
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 81321.7 (22h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 247024
telemt_connections_bad_total 13611
telemt_handshake_timeouts_total 1832
telemt_upstream_connect_attempt_total 34684
telemt_upstream_connect_success_total 24764
telemt_upstream_connect_fail_total 9920
telemt_upstream_connect_attempts_per_request{bucket="1"} 34684
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12458
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12123
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 175
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9920
telemt_me_keepalive_timeout_total 3342
telemt_me_reconnect_attempts_total 69366
telemt_me_reconnect_success_total 17831
telemt_me_reader_eof_total 19978
telemt_me_idle_close_by_peer_total 19971
telemt_me_route_drop_no_conn_total 89732
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 207799
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 616
telemt_desync_full_logged_total 178
telemt_desync_suppressed_total 438
telemt_desync_frames_bucket_total{bucket="1_2"} 151
telemt_desync_frames_bucket_total{bucket="3_10"} 236
telemt_desync_frames_bucket_total{bucket="gt_10"} 229
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 19671
telemt_me_refill_failed_total 1606
telemt_me_writer_restored_same_endpoint_total 17821
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1840
telemt_user_connections_total{user="hello"} 210539
telemt_user_connections_current{user="hello"} 183
telemt_user_octets_from_client{user="hello"} 3324737222 (3.10 GB)
telemt_user_octets_to_client{user="hello"} 82019499613 (76.39 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 31493.5 (8h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 35382
telemt_connections_bad_total 6572
telemt_handshake_timeouts_total 149
telemt_upstream_connect_attempt_total 10899
telemt_upstream_connect_success_total 10796
telemt_upstream_connect_fail_total 103
telemt_upstream_connect_attempts_per_request{bucket="1"} 10899
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4686
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6071
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 39
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 103
telemt_me_keepalive_timeout_total 257
telemt_me_reconnect_attempts_total 10190
telemt_me_reconnect_success_total 9228
telemt_me_reader_eof_total 9799
telemt_me_idle_close_by_peer_total 9799
telemt_me_route_drop_no_conn_total 9695
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 27740
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 9340
telemt_me_refill_failed_total 29
telemt_me_writer_restored_same_endpoint_total 9210
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 112
telemt_user_connections_total{user="hello"} 27740
telemt_user_connections_current{user="hello"} 70
telemt_user_octets_from_client{user="hello"} 211163076 (201.38 MB)
telemt_user_octets_to_client{user="hello"} 9876941360 (9.20 GB)
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 81278.2 (22h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 416422
telemt_connections_bad_total 8034
telemt_handshake_timeouts_total 3177
telemt_upstream_connect_attempt_total 17373
telemt_upstream_connect_success_total 17277
telemt_upstream_connect_fail_total 96
telemt_upstream_connect_attempts_per_request{bucket="1"} 17373
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8044
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9208
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 96
telemt_me_keepalive_timeout_total 1452
telemt_me_reconnect_attempts_total 16857
telemt_me_reconnect_success_total 13224
telemt_me_reader_eof_total 14204
telemt_me_idle_close_by_peer_total 14201
telemt_me_route_drop_no_conn_total 185109
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 403927
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 358
telemt_desync_full_logged_total 135
telemt_desync_suppressed_total 223
telemt_desync_frames_bucket_total{bucket="1_2"} 86
telemt_desync_frames_bucket_total{bucket="3_10"} 127
telemt_desync_frames_bucket_total{bucket="gt_10"} 145
telemt_pool_swap_total 76
telemt_me_writer_removed_unexpected_total 13502
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 13217
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 278
telemt_user_connections_total{user="hello"} 392170
telemt_user_connections_current{user="hello"} 378
telemt_user_octets_from_client{user="hello"} 6421405848 (5.98 GB)
telemt_user_octets_to_client{user="hello"} 231171062604 (215.29 GB)
telemt_user_unique_ips_current{user="hello"} 149
telemt_user_unique_ips_recent_window{user="hello"} 55
```