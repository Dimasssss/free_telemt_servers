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

# Server Metrics 2026-03-15 23:18:35 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 90245.9 (25h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 402643
telemt_connections_bad_total 5286
telemt_handshake_timeouts_total 14023
telemt_upstream_connect_attempt_total 21552
telemt_upstream_connect_success_total 21449
telemt_upstream_connect_fail_total 103
telemt_upstream_connect_attempts_per_request{bucket="1"} 21552
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9495
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11907
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 103
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 32
telemt_me_reconnect_attempts_total 20362
telemt_me_reconnect_success_total 16955
telemt_me_reader_eof_total 18101
telemt_me_idle_close_by_peer_total 18101
telemt_me_route_drop_no_conn_total 488241
telemt_me_route_drop_channel_closed_total 78
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 429336
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2115
telemt_desync_full_logged_total 835
telemt_desync_suppressed_total 1280
telemt_desync_frames_bucket_total{bucket="1_2"} 409
telemt_desync_frames_bucket_total{bucket="3_10"} 812
telemt_desync_frames_bucket_total{bucket="gt_10"} 894
telemt_pool_swap_total 84
telemt_me_writer_removed_unexpected_total 17247
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 16921
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 292
telemt_user_connections_total{user="hello"} 368398
telemt_user_connections_current{user="hello"} 193
telemt_user_octets_from_client{user="hello"} 8041761584 (7.49 GB)
telemt_user_octets_to_client{user="hello"} 276646612768 (257.65 GB)
telemt_user_unique_ips_current{user="hello"} 75
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 90252.3 (25h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 168164
telemt_connections_bad_total 2906
telemt_handshake_timeouts_total 14067
telemt_upstream_connect_attempt_total 24587
telemt_upstream_connect_success_total 24512
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 24587
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10676
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13228
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 608
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 1305
telemt_me_reconnect_attempts_total 26494
telemt_me_reconnect_success_total 19599
telemt_me_reader_eof_total 20971
telemt_me_idle_close_by_peer_total 20970
telemt_me_route_drop_no_conn_total 68175
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 144328
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 24
telemt_desync_full_logged_total 8
telemt_desync_suppressed_total 16
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 9
telemt_pool_swap_total 75
telemt_me_writer_removed_unexpected_total 20106
telemt_me_refill_failed_total 208
telemt_me_writer_restored_same_endpoint_total 19583
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 507
telemt_user_connections_total{user="hello"} 144597
telemt_user_connections_current{user="hello"} 168
telemt_user_octets_from_client{user="hello"} 3340543909 (3.11 GB)
telemt_user_octets_to_client{user="hello"} 76320816960 (71.08 GB)
telemt_user_msgs_from_client{user="hello"} 721
telemt_user_msgs_to_client{user="hello"} 1482
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 90244.7 (25h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 166993
telemt_connections_bad_total 1768
telemt_handshake_timeouts_total 3514
telemt_upstream_connect_attempt_total 25743
telemt_upstream_connect_success_total 25735
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 25743
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11142
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14545
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 35
telemt_me_reconnect_attempts_total 28553
telemt_me_reconnect_success_total 21178
telemt_me_reader_eof_total 22774
telemt_me_idle_close_by_peer_total 22773
telemt_me_route_drop_no_conn_total 65840
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 149077
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 60
telemt_desync_full_logged_total 24
telemt_desync_suppressed_total 36
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 30
telemt_desync_frames_bucket_total{bucket="gt_10"} 25
telemt_pool_swap_total 79
telemt_me_writer_removed_unexpected_total 21612
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 21170
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 434
telemt_user_connections_total{user="hello"} 148959
telemt_user_connections_current{user="hello"} 89
telemt_user_octets_from_client{user="hello"} 13086101936 (12.19 GB)
telemt_user_octets_to_client{user="hello"} 97341506352 (90.66 GB)
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 90244.7 (25h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 244803
telemt_connections_bad_total 1202
telemt_handshake_timeouts_total 1619
telemt_upstream_connect_attempt_total 21061
telemt_upstream_connect_success_total 21042
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 21061
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10082
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10864
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_keepalive_timeout_total 20
telemt_me_reconnect_attempts_total 16646
telemt_me_reconnect_success_total 16546
telemt_me_reader_eof_total 17640
telemt_me_idle_close_by_peer_total 17640
telemt_me_route_drop_no_conn_total 89141
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 226130
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 862
telemt_desync_full_logged_total 298
telemt_desync_suppressed_total 564
telemt_desync_frames_bucket_total{bucket="1_2"} 175
telemt_desync_frames_bucket_total{bucket="3_10"} 365
telemt_desync_frames_bucket_total{bucket="gt_10"} 322
telemt_pool_swap_total 86
telemt_me_writer_removed_unexpected_total 16741
telemt_me_writer_restored_same_endpoint_total 16535
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 195
telemt_user_connections_total{user="hello"} 226042
telemt_user_connections_current{user="hello"} 125
telemt_user_octets_from_client{user="hello"} 4091815932 (3.81 GB)
telemt_user_octets_to_client{user="hello"} 106410490056 (99.10 GB)
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 65316.1 (18h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 153842
telemt_connections_bad_total 28417
telemt_handshake_timeouts_total 2814
telemt_upstream_connect_attempt_total 18816
telemt_upstream_connect_success_total 18707
telemt_upstream_connect_fail_total 109
telemt_upstream_connect_attempts_per_request{bucket="1"} 18816
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8427
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10168
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 112
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 109
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 109739
telemt_me_reconnect_success_total 15280
telemt_me_reader_eof_total 16147
telemt_me_idle_close_by_peer_total 16147
telemt_me_route_drop_no_conn_total 49163
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 118273
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 337
telemt_desync_full_logged_total 78
telemt_desync_suppressed_total 259
telemt_desync_frames_bucket_total{bucket="1_2"} 51
telemt_desync_frames_bucket_total{bucket="3_10"} 127
telemt_desync_frames_bucket_total{bucket="gt_10"} 159
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 15390
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 15176
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 110
telemt_user_connections_total{user="hello"} 118399
telemt_user_connections_current{user="hello"} 44
telemt_user_octets_from_client{user="hello"} 1770449657 (1.65 GB)
telemt_user_octets_to_client{user="hello"} 42648937503 (39.72 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 21
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 90243.9 (25h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 608047
telemt_connections_bad_total 58577
telemt_handshake_timeouts_total 4723
telemt_upstream_connect_attempt_total 19083
telemt_upstream_connect_success_total 18977
telemt_upstream_connect_fail_total 106
telemt_upstream_connect_attempts_per_request{bucket="1"} 19083
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9074
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9862
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 106
telemt_me_keepalive_timeout_total 62
telemt_me_reconnect_attempts_total 15769
telemt_me_reconnect_success_total 14454
telemt_me_reader_eof_total 15393
telemt_me_idle_close_by_peer_total 15393
telemt_me_route_drop_no_conn_total 542376
telemt_me_route_drop_channel_closed_total 95
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 642926
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 324
telemt_desync_full_logged_total 91
telemt_desync_suppressed_total 233
telemt_desync_frames_bucket_total{bucket="1_2"} 169
telemt_desync_frames_bucket_total{bucket="3_10"} 95
telemt_desync_frames_bucket_total{bucket="gt_10"} 60
telemt_pool_swap_total 81
telemt_me_writer_removed_unexpected_total 14657
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 14427
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 203
telemt_user_connections_total{user="hello"} 509750
telemt_user_connections_current{user="hello"} 320
telemt_user_octets_from_client{user="hello"} 12475138800 (11.62 GB)
telemt_user_octets_to_client{user="hello"} 315333338680 (293.68 GB)
telemt_user_unique_ips_current{user="hello"} 143
telemt_user_unique_ips_recent_window{user="hello"} 48
```