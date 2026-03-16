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

# Server Metrics 2026-03-16 07:23:36 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 119346.7 (33h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 545319
telemt_connections_bad_total 5708
telemt_handshake_timeouts_total 19102
telemt_upstream_connect_attempt_total 28032
telemt_upstream_connect_success_total 27900
telemt_upstream_connect_fail_total 132
telemt_upstream_connect_attempts_per_request{bucket="1"} 28032
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12382
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15471
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 132
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 51
telemt_me_reconnect_attempts_total 25432
telemt_me_reconnect_success_total 21998
telemt_me_reader_eof_total 23538
telemt_me_idle_close_by_peer_total 23538
telemt_me_route_drop_no_conn_total 521625
telemt_me_route_drop_channel_closed_total 83
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 543174
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2638
telemt_desync_full_logged_total 1048
telemt_desync_suppressed_total 1590
telemt_desync_frames_bucket_total{bucket="1_2"} 549
telemt_desync_frames_bucket_total{bucket="3_10"} 1020
telemt_desync_frames_bucket_total{bucket="gt_10"} 1069
telemt_pool_swap_total 116
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 22349
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 21964
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 351
telemt_user_connections_total{user="hello"} 481998
telemt_user_connections_current{user="hello"} 514
telemt_user_octets_from_client{user="hello"} 9398624420 (8.75 GB)
telemt_user_octets_to_client{user="hello"} 315731504476 (294.05 GB)
telemt_user_unique_ips_current{user="hello"} 156
telemt_user_unique_ips_recent_window{user="hello"} 68
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 119353.0 (33h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 217104
telemt_connections_bad_total 3155
telemt_handshake_timeouts_total 15049
telemt_upstream_connect_attempt_total 32054
telemt_upstream_connect_success_total 31979
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 32054
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13870
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17489
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 620
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 1307
telemt_me_reconnect_attempts_total 32575
telemt_me_reconnect_success_total 25656
telemt_me_reader_eof_total 27495
telemt_me_idle_close_by_peer_total 27494
telemt_me_route_drop_no_conn_total 107132
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 191168
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 92
telemt_desync_full_logged_total 26
telemt_desync_suppressed_total 66
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 36
telemt_desync_frames_bucket_total{bucket="gt_10"} 43
telemt_pool_swap_total 106
telemt_me_writer_removed_unexpected_total 26222
telemt_me_refill_failed_total 208
telemt_me_writer_restored_same_endpoint_total 25640
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 566
telemt_user_connections_total{user="hello"} 190702
telemt_user_connections_current{user="hello"} 286
telemt_user_octets_from_client{user="hello"} 4414073829 (4.11 GB)
telemt_user_octets_to_client{user="hello"} 106723219876 (99.39 GB)
telemt_user_msgs_from_client{user="hello"} 721
telemt_user_msgs_to_client{user="hello"} 1482
telemt_user_unique_ips_current{user="hello"} 76
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 119345.4 (33h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 235898
telemt_connections_bad_total 5729
telemt_handshake_timeouts_total 4594
telemt_upstream_connect_attempt_total 33245
telemt_upstream_connect_success_total 33237
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 33245
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14431
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18752
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 39
telemt_me_reconnect_attempts_total 34667
telemt_me_reconnect_success_total 27268
telemt_me_reader_eof_total 29359
telemt_me_idle_close_by_peer_total 29358
telemt_me_route_drop_no_conn_total 82679
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 187846
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 78
telemt_desync_full_logged_total 29
telemt_desync_suppressed_total 49
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 36
telemt_desync_frames_bucket_total{bucket="gt_10"} 35
telemt_pool_swap_total 110
telemt_me_writer_removed_unexpected_total 27763
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 27260
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 495
telemt_user_connections_total{user="hello"} 187558
telemt_user_connections_current{user="hello"} 186
telemt_user_octets_from_client{user="hello"} 17294088517 (16.11 GB)
telemt_user_octets_to_client{user="hello"} 111148728160 (103.52 GB)
telemt_user_msgs_from_client{user="hello"} 7
telemt_user_msgs_to_client{user="hello"} 46
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 119345.1 (33h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 318992
telemt_connections_bad_total 1332
telemt_handshake_timeouts_total 2905
telemt_upstream_connect_attempt_total 27693
telemt_upstream_connect_success_total 27662
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 27693
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13244
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14267
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 138
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 21873
telemt_me_reconnect_success_total 21737
telemt_me_reader_eof_total 23213
telemt_me_idle_close_by_peer_total 23212
telemt_me_route_drop_no_conn_total 113511
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 293775
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1019
telemt_desync_full_logged_total 354
telemt_desync_suppressed_total 665
telemt_desync_frames_bucket_total{bucket="1_2"} 207
telemt_desync_frames_bucket_total{bucket="3_10"} 440
telemt_desync_frames_bucket_total{bucket="gt_10"} 372
telemt_pool_swap_total 116
telemt_me_writer_removed_unexpected_total 22019
telemt_me_writer_restored_same_endpoint_total 21726
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 282
telemt_user_connections_total{user="hello"} 293657
telemt_user_connections_current{user="hello"} 326
telemt_user_octets_from_client{user="hello"} 4772010074 (4.44 GB)
telemt_user_octets_to_client{user="hello"} 126289913492 (117.62 GB)
telemt_user_msgs_from_client{user="hello"} 25
telemt_user_msgs_to_client{user="hello"} 50
telemt_user_unique_ips_current{user="hello"} 89
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 94416.3 (26h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 212267
telemt_connections_bad_total 35685
telemt_handshake_timeouts_total 3608
telemt_upstream_connect_attempt_total 26982
telemt_upstream_connect_success_total 26835
telemt_upstream_connect_fail_total 147
telemt_upstream_connect_attempts_per_request{bucket="1"} 26982
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11884
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14810
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 141
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 147
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 116482
telemt_me_reconnect_success_total 21993
telemt_me_reader_eof_total 23355
telemt_me_idle_close_by_peer_total 23355
telemt_me_route_drop_no_conn_total 66710
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 167512
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 480
telemt_desync_full_logged_total 120
telemt_desync_suppressed_total 360
telemt_desync_frames_bucket_total{bucket="1_2"} 65
telemt_desync_frames_bucket_total{bucket="3_10"} 204
telemt_desync_frames_bucket_total{bucket="gt_10"} 211
telemt_pool_swap_total 81
telemt_me_writer_removed_unexpected_total 22172
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 21889
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 179
telemt_user_connections_total{user="hello"} 167142
telemt_user_connections_current{user="hello"} 137
telemt_user_octets_from_client{user="hello"} 2307193105 (2.15 GB)
telemt_user_octets_to_client{user="hello"} 71997256643 (67.05 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 53
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 119344.3 (33h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 779221
telemt_connections_bad_total 67320
telemt_handshake_timeouts_total 5972
telemt_upstream_connect_attempt_total 25126
telemt_upstream_connect_success_total 24994
telemt_upstream_connect_fail_total 132
telemt_upstream_connect_attempts_per_request{bucket="1"} 25126
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11936
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13016
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 132
telemt_me_keepalive_timeout_total 62
telemt_me_reconnect_attempts_total 20402
telemt_me_reconnect_success_total 19057
telemt_me_reader_eof_total 20354
telemt_me_idle_close_by_peer_total 20354
telemt_me_route_drop_no_conn_total 633201
telemt_me_route_drop_channel_closed_total 103
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 782779
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 336
telemt_desync_full_logged_total 96
telemt_desync_suppressed_total 240
telemt_desync_frames_bucket_total{bucket="1_2"} 171
telemt_desync_frames_bucket_total{bucket="3_10"} 98
telemt_desync_frames_bucket_total{bucket="gt_10"} 67
telemt_pool_swap_total 113
telemt_me_writer_removed_unexpected_total 19324
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 19030
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 267
telemt_user_connections_total{user="hello"} 641422
telemt_user_connections_current{user="hello"} 563
telemt_user_octets_from_client{user="hello"} 14202239292 (13.23 GB)
telemt_user_octets_to_client{user="hello"} 385290393688 (358.83 GB)
telemt_user_unique_ips_current{user="hello"} 205
telemt_user_unique_ips_recent_window{user="hello"} 89
```