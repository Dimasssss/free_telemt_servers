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

# Server Metrics 2026-03-13 08:34:56 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 90092.2 (25h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 350670
telemt_connections_bad_total 3176
telemt_handshake_timeouts_total 7675
telemt_upstream_connect_attempt_total 22506
telemt_upstream_connect_success_total 22400
telemt_upstream_connect_fail_total 106
telemt_upstream_connect_attempts_per_request{bucket="1"} 22506
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10072
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12280
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 106
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1669
telemt_me_reconnect_attempts_total 21385
telemt_me_reconnect_success_total 17878
telemt_me_reader_eof_total 19119
telemt_me_idle_close_by_peer_total 19118
telemt_me_route_drop_no_conn_total 109387
telemt_me_route_drop_channel_closed_total 21
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 299419
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 976
telemt_desync_full_logged_total 361
telemt_desync_suppressed_total 615
telemt_desync_frames_bucket_total{bucket="1_2"} 198
telemt_desync_frames_bucket_total{bucket="3_10"} 357
telemt_desync_frames_bucket_total{bucket="gt_10"} 421
telemt_pool_swap_total 82
telemt_me_writer_removed_unexpected_total 18176
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 17862
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 298
telemt_user_connections_total{user="hello"} 299110
telemt_user_connections_current{user="hello"} 320
telemt_user_octets_from_client{user="hello"} 4905190524 (4.57 GB)
telemt_user_octets_to_client{user="hello"} 136282521132 (126.92 GB)
telemt_user_unique_ips_current{user="hello"} 98
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 89984.6 (24h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 159559
telemt_connections_bad_total 1493
telemt_handshake_timeouts_total 1205
telemt_upstream_connect_attempt_total 45355
telemt_upstream_connect_success_total 44739
telemt_upstream_connect_fail_total 616
telemt_upstream_connect_attempts_per_request{bucket="1"} 45355
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26053
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18174
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 512
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 616
telemt_me_keepalive_timeout_total 693
telemt_me_reconnect_attempts_total 79139
telemt_me_reconnect_success_total 23768
telemt_me_reader_eof_total 26203
telemt_me_idle_close_by_peer_total 26203
telemt_me_route_drop_no_conn_total 60314
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 133965
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 19
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
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 25691
telemt_me_refill_failed_total 1728
telemt_me_writer_restored_same_endpoint_total 23753
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1923
telemt_user_connections_total{user="hello"} 150455
telemt_user_connections_current{user="hello"} 161
telemt_user_octets_from_client{user="hello"} 1557344408 (1.45 GB)
telemt_user_octets_to_client{user="hello"} 48320680903 (45.00 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 89948.3 (24h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 192604
telemt_connections_bad_total 1993
telemt_handshake_timeouts_total 3385
telemt_upstream_connect_attempt_total 24404
telemt_upstream_connect_success_total 24401
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 24404
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11201
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13175
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 582
telemt_me_reconnect_attempts_total 21066
telemt_me_reconnect_success_total 19883
telemt_me_reader_eof_total 21312
telemt_me_idle_close_by_peer_total 21312
telemt_me_route_drop_no_conn_total 73892
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 180152
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
telemt_pool_swap_total 82
telemt_me_writer_removed_unexpected_total 20103
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 19863
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 220
telemt_user_connections_total{user="hello"} 180080
telemt_user_connections_current{user="hello"} 128
telemt_user_octets_from_client{user="hello"} 6717250228 (6.26 GB)
telemt_user_octets_to_client{user="hello"} 75580952088 (70.39 GB)
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 89923.9 (24h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 279113
telemt_connections_bad_total 13652
telemt_handshake_timeouts_total 2099
telemt_upstream_connect_attempt_total 37262
telemt_upstream_connect_success_total 27295
telemt_upstream_connect_fail_total 9967
telemt_upstream_connect_attempts_per_request{bucket="1"} 37262
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13628
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13476
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 182
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9967
telemt_me_keepalive_timeout_total 3381
telemt_me_reconnect_attempts_total 71505
telemt_me_reconnect_success_total 19959
telemt_me_reader_eof_total 22204
telemt_me_idle_close_by_peer_total 22197
telemt_me_route_drop_no_conn_total 100594
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 237392
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 872
telemt_desync_full_logged_total 259
telemt_desync_suppressed_total 613
telemt_desync_frames_bucket_total{bucket="1_2"} 223
telemt_desync_frames_bucket_total{bucket="3_10"} 323
telemt_desync_frames_bucket_total{bucket="gt_10"} 326
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 21826
telemt_me_refill_failed_total 1606
telemt_me_writer_restored_same_endpoint_total 19949
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1867
telemt_user_connections_total{user="hello"} 240118
telemt_user_connections_current{user="hello"} 168
telemt_user_octets_from_client{user="hello"} 5364568858 (5.00 GB)
telemt_user_octets_to_client{user="hello"} 91389158325 (85.11 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 40095.4 (11h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 50738
telemt_connections_bad_total 8144
telemt_handshake_timeouts_total 416
telemt_upstream_connect_attempt_total 13918
telemt_upstream_connect_success_total 13778
telemt_upstream_connect_fail_total 140
telemt_upstream_connect_attempts_per_request{bucket="1"} 13918
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6035
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7694
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 49
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 140
telemt_me_keepalive_timeout_total 325
telemt_me_reconnect_attempts_total 13984
telemt_me_reconnect_success_total 11765
telemt_me_reader_eof_total 12524
telemt_me_idle_close_by_peer_total 12524
telemt_me_route_drop_no_conn_total 15328
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 40770
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 71
telemt_desync_full_logged_total 9
telemt_desync_suppressed_total 62
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 27
telemt_desync_frames_bucket_total{bucket="gt_10"} 37
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 11935
telemt_me_refill_failed_total 68
telemt_me_writer_restored_same_endpoint_total 11747
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 170
telemt_user_connections_total{user="hello"} 40769
telemt_user_connections_current{user="hello"} 63
telemt_user_octets_from_client{user="hello"} 292802660 (279.24 MB)
telemt_user_octets_to_client{user="hello"} 11517818860 (10.73 GB)
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 89880.3 (24h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 478435
telemt_connections_bad_total 13341
telemt_handshake_timeouts_total 4381
telemt_upstream_connect_attempt_total 18971
telemt_upstream_connect_success_total 18869
telemt_upstream_connect_fail_total 102
telemt_upstream_connect_attempts_per_request{bucket="1"} 18971
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8827
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10017
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 102
telemt_me_keepalive_timeout_total 1536
telemt_me_reconnect_attempts_total 18060
telemt_me_reconnect_success_total 14419
telemt_me_reader_eof_total 15487
telemt_me_idle_close_by_peer_total 15484
telemt_me_route_drop_no_conn_total 247698
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 469503
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 391
telemt_desync_full_logged_total 148
telemt_desync_suppressed_total 243
telemt_desync_frames_bucket_total{bucket="1_2"} 92
telemt_desync_frames_bucket_total{bucket="3_10"} 140
telemt_desync_frames_bucket_total{bucket="gt_10"} 159
telemt_pool_swap_total 85
telemt_me_writer_removed_unexpected_total 14717
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 14412
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 298
telemt_user_connections_total{user="hello"} 443722
telemt_user_connections_current{user="hello"} 466
telemt_user_octets_from_client{user="hello"} 8195174720 (7.63 GB)
telemt_user_octets_to_client{user="hello"} 253566514336 (236.15 GB)
telemt_user_unique_ips_current{user="hello"} 172
telemt_user_unique_ips_recent_window{user="hello"} 71
```