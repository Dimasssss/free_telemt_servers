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

# Server Metrics 2026-03-13 06:32:02 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 82718.1 (22h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 313160
telemt_connections_bad_total 3129
telemt_handshake_timeouts_total 6698
telemt_upstream_connect_attempt_total 20833
telemt_upstream_connect_success_total 20735
telemt_upstream_connect_fail_total 98
telemt_upstream_connect_attempts_per_request{bucket="1"} 20833
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9342
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11345
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 98
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1620
telemt_me_reconnect_attempts_total 20097
telemt_me_reconnect_success_total 16595
telemt_me_reader_eof_total 17741
telemt_me_idle_close_by_peer_total 17740
telemt_me_route_drop_no_conn_total 97343
telemt_me_route_drop_channel_closed_total 16
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 264632
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 926
telemt_desync_full_logged_total 343
telemt_desync_suppressed_total 583
telemt_desync_frames_bucket_total{bucket="1_2"} 184
telemt_desync_frames_bucket_total{bucket="3_10"} 336
telemt_desync_frames_bucket_total{bucket="gt_10"} 406
telemt_pool_swap_total 74
telemt_me_writer_removed_unexpected_total 16883
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 16579
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 288
telemt_user_connections_total{user="hello"} 264563
telemt_user_connections_current{user="hello"} 281
telemt_user_octets_from_client{user="hello"} 4488718744 (4.18 GB)
telemt_user_octets_to_client{user="hello"} 126206524952 (117.54 GB)
telemt_user_unique_ips_current{user="hello"} 93
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 82611.0 (22h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 143524
telemt_connections_bad_total 1421
telemt_handshake_timeouts_total 1062
telemt_upstream_connect_attempt_total 43128
telemt_upstream_connect_success_total 42570
telemt_upstream_connect_fail_total 558
telemt_upstream_connect_attempts_per_request{bucket="1"} 43128
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25187
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16874
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 509
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 558
telemt_me_keepalive_timeout_total 626
telemt_me_reconnect_attempts_total 71141
telemt_me_reconnect_success_total 21949
telemt_me_reader_eof_total 24157
telemt_me_idle_close_by_peer_total 24157
telemt_me_route_drop_no_conn_total 54085
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 119344
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
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 23656
telemt_me_refill_failed_total 1535
telemt_me_writer_restored_same_endpoint_total 21934
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1707
telemt_user_connections_total{user="hello"} 135839
telemt_user_connections_current{user="hello"} 142
telemt_user_octets_from_client{user="hello"} 1406500952 (1.31 GB)
telemt_user_octets_to_client{user="hello"} 42983591687 (40.03 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 82574.6 (22h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 173801
telemt_connections_bad_total 1911
telemt_handshake_timeouts_total 2847
telemt_upstream_connect_attempt_total 22632
telemt_upstream_connect_success_total 22630
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 22632
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10424
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12183
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 501
telemt_me_reconnect_attempts_total 19643
telemt_me_reconnect_success_total 18471
telemt_me_reader_eof_total 19799
telemt_me_idle_close_by_peer_total 19799
telemt_me_route_drop_no_conn_total 67091
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 162585
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
telemt_pool_swap_total 75
telemt_me_writer_removed_unexpected_total 18671
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 18451
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 200
telemt_user_connections_total{user="hello"} 162513
telemt_user_connections_current{user="hello"} 110
telemt_user_octets_from_client{user="hello"} 2958870204 (2.76 GB)
telemt_user_octets_to_client{user="hello"} 72971649968 (67.96 GB)
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 82550.3 (22h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 250790
telemt_connections_bad_total 13611
telemt_handshake_timeouts_total 1915
telemt_upstream_connect_attempt_total 35068
telemt_upstream_connect_success_total 25145
telemt_upstream_connect_fail_total 9923
telemt_upstream_connect_attempts_per_request{bucket="1"} 35068
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12629
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12332
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 175
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9923
telemt_me_keepalive_timeout_total 3348
telemt_me_reconnect_attempts_total 69704
telemt_me_reconnect_success_total 18168
telemt_me_reader_eof_total 20343
telemt_me_idle_close_by_peer_total 20336
telemt_me_route_drop_no_conn_total 91003
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 211210
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 640
telemt_desync_full_logged_total 186
telemt_desync_suppressed_total 454
telemt_desync_frames_bucket_total{bucket="1_2"} 158
telemt_desync_frames_bucket_total{bucket="3_10"} 243
telemt_desync_frames_bucket_total{bucket="gt_10"} 239
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 20009
telemt_me_refill_failed_total 1606
telemt_me_writer_restored_same_endpoint_total 18158
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1841
telemt_user_connections_total{user="hello"} 213951
telemt_user_connections_current{user="hello"} 172
telemt_user_octets_from_client{user="hello"} 4303405214 (4.01 GB)
telemt_user_octets_to_client{user="hello"} 82681370361 (77.00 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 32721.8 (9h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 37538
telemt_connections_bad_total 6792
telemt_handshake_timeouts_total 160
telemt_upstream_connect_attempt_total 11331
telemt_upstream_connect_success_total 11221
telemt_upstream_connect_fail_total 110
telemt_upstream_connect_attempts_per_request{bucket="1"} 11331
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4876
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6305
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 110
telemt_me_keepalive_timeout_total 269
telemt_me_reconnect_attempts_total 10529
telemt_me_reconnect_success_total 9565
telemt_me_reader_eof_total 10203
telemt_me_idle_close_by_peer_total 10203
telemt_me_route_drop_no_conn_total 10369
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 29616
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 9680
telemt_me_refill_failed_total 29
telemt_me_writer_restored_same_endpoint_total 9547
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 115
telemt_user_connections_total{user="hello"} 29616
telemt_user_connections_current{user="hello"} 58
telemt_user_octets_from_client{user="hello"} 225562216 (215.11 MB)
telemt_user_octets_to_client{user="hello"} 10030666256 (9.34 GB)
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 82506.7 (22h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 423114
telemt_connections_bad_total 8064
telemt_handshake_timeouts_total 3227
telemt_upstream_connect_attempt_total 17584
telemt_upstream_connect_success_total 17488
telemt_upstream_connect_fail_total 96
telemt_upstream_connect_attempts_per_request{bucket="1"} 17584
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8146
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9317
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 96
telemt_me_keepalive_timeout_total 1455
telemt_me_reconnect_attempts_total 17025
telemt_me_reconnect_success_total 13391
telemt_me_reader_eof_total 14380
telemt_me_idle_close_by_peer_total 14377
telemt_me_route_drop_no_conn_total 187796
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 410287
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 361
telemt_desync_full_logged_total 138
telemt_desync_suppressed_total 223
telemt_desync_frames_bucket_total{bucket="1_2"} 87
telemt_desync_frames_bucket_total{bucket="3_10"} 128
telemt_desync_frames_bucket_total{bucket="gt_10"} 146
telemt_pool_swap_total 77
telemt_me_writer_removed_unexpected_total 13671
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 13384
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 280
telemt_user_connections_total{user="hello"} 398521
telemt_user_connections_current{user="hello"} 385
telemt_user_octets_from_client{user="hello"} 6495278336 (6.05 GB)
telemt_user_octets_to_client{user="hello"} 233110637596 (217.10 GB)
telemt_user_unique_ips_current{user="hello"} 145
telemt_user_unique_ips_recent_window{user="hello"} 61
```