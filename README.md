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

# Server Metrics 2026-03-12 20:03:29 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 44987.9 (12h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 222277
telemt_connections_bad_total 2622
telemt_handshake_timeouts_total 5007
telemt_upstream_connect_attempt_total 11299
telemt_upstream_connect_success_total 11248
telemt_upstream_connect_fail_total 51
telemt_upstream_connect_attempts_per_request{bucket="1"} 11299
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4973
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 51
telemt_me_keepalive_timeout_total 1440
telemt_me_reconnect_attempts_total 12423
telemt_me_reconnect_success_total 8962
telemt_me_reader_eof_total 9508
telemt_me_idle_close_by_peer_total 9507
telemt_me_route_drop_no_conn_total 67466
telemt_me_route_drop_channel_closed_total 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 185492
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 643
telemt_desync_full_logged_total 242
telemt_desync_suppressed_total 401
telemt_desync_frames_bucket_total{bucket="1_2"} 121
telemt_desync_frames_bucket_total{bucket="3_10"} 244
telemt_desync_frames_bucket_total{bucket="gt_10"} 278
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 9176
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 8946
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 214
telemt_user_connections_total{user="hello"} 185447
telemt_user_connections_current{user="hello"} 310
telemt_user_octets_from_client{user="hello"} 3476393272 (3.24 GB)
telemt_user_octets_to_client{user="hello"} 87360292160 (81.36 GB)
telemt_user_unique_ips_current{user="hello"} 81
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 44881.5 (12h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 99933
telemt_connections_bad_total 534
telemt_handshake_timeouts_total 778
telemt_upstream_connect_attempt_total 28374
telemt_upstream_connect_success_total 28084
telemt_upstream_connect_fail_total 290
telemt_upstream_connect_attempts_per_request{bucket="1"} 28374
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19469
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8130
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 485
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 290
telemt_me_keepalive_timeout_total 338
telemt_me_reconnect_attempts_total 48743
telemt_me_reconnect_success_total 9311
telemt_me_reader_eof_total 10717
telemt_me_idle_close_by_peer_total 10717
telemt_me_route_drop_no_conn_total 36414
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 78420
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 31
telemt_desync_full_logged_total 9
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 17
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 10616
telemt_me_refill_failed_total 1231
telemt_me_writer_restored_same_endpoint_total 9296
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1305
telemt_user_connections_total{user="hello"} 94924
telemt_user_connections_current{user="hello"} 89
telemt_user_octets_from_client{user="hello"} 1034440772 (986.52 MB)
telemt_user_octets_to_client{user="hello"} 27876063223 (25.96 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 44845.1 (12h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 125442
telemt_connections_bad_total 1530
telemt_handshake_timeouts_total 2186
telemt_upstream_connect_attempt_total 12445
telemt_upstream_connect_success_total 12444
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 12445
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5945
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6482
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 285
telemt_me_reconnect_attempts_total 11275
telemt_me_reconnect_success_total 10139
telemt_me_reader_eof_total 10776
telemt_me_idle_close_by_peer_total 10776
telemt_me_route_drop_no_conn_total 47204
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 116806
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 41
telemt_desync_full_logged_total 19
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 11
telemt_desync_frames_bucket_total{bucket="gt_10"} 28
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 10274
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 10119
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 135
telemt_user_connections_total{user="hello"} 116778
telemt_user_connections_current{user="hello"} 129
telemt_user_octets_from_client{user="hello"} 2492394228 (2.32 GB)
telemt_user_octets_to_client{user="hello"} 56515531392 (52.63 GB)
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 44820.9 (12h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 181495
telemt_connections_bad_total 13153
telemt_handshake_timeouts_total 1272
telemt_upstream_connect_attempt_total 23195
telemt_upstream_connect_success_total 13567
telemt_upstream_connect_fail_total 9628
telemt_upstream_connect_attempts_per_request{bucket="1"} 23195
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7547
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5913
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 99
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9628
telemt_me_keepalive_timeout_total 2431
telemt_me_reconnect_attempts_total 39613
telemt_me_reconnect_success_total 8431
telemt_me_reader_eof_total 9678
telemt_me_idle_close_by_peer_total 9671
telemt_me_route_drop_no_conn_total 62246
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 146173
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 482
telemt_desync_full_logged_total 141
telemt_desync_suppressed_total 341
telemt_desync_frames_bucket_total{bucket="1_2"} 122
telemt_desync_frames_bucket_total{bucket="3_10"} 178
telemt_desync_frames_bucket_total{bucket="gt_10"} 182
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 9550
telemt_me_refill_failed_total 971
telemt_me_writer_restored_same_endpoint_total 8421
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1119
telemt_user_connections_total{user="hello"} 148929
telemt_user_connections_current{user="hello"} 142
telemt_user_octets_from_client{user="hello"} 2738707978 (2.55 GB)
telemt_user_octets_to_client{user="hello"} 58596572277 (54.57 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## rdp-onedash.ru

Не удалось получить метрики для этого сервера.

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 44777.3 (12h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 282240
telemt_connections_bad_total 2162
telemt_handshake_timeouts_total 2195
telemt_upstream_connect_attempt_total 9400
telemt_upstream_connect_success_total 9353
telemt_upstream_connect_fail_total 47
telemt_upstream_connect_attempts_per_request{bucket="1"} 9400
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4360
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4983
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 47
telemt_me_keepalive_timeout_total 484
telemt_me_reconnect_attempts_total 10704
telemt_me_reconnect_success_total 7098
telemt_me_reader_eof_total 7570
telemt_me_idle_close_by_peer_total 7569
telemt_me_route_drop_no_conn_total 131600
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 280948
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 274
telemt_desync_full_logged_total 105
telemt_desync_suppressed_total 169
telemt_desync_frames_bucket_total{bucket="1_2"} 74
telemt_desync_frames_bucket_total{bucket="3_10"} 104
telemt_desync_frames_bucket_total{bucket="gt_10"} 96
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 7301
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 7091
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 203
telemt_user_connections_total{user="hello"} 269256
telemt_user_connections_current{user="hello"} 341
telemt_user_octets_from_client{user="hello"} 4973081048 (4.63 GB)
telemt_user_octets_to_client{user="hello"} 135122988556 (125.84 GB)
telemt_user_unique_ips_current{user="hello"} 117
telemt_user_unique_ips_recent_window{user="hello"} 41
```