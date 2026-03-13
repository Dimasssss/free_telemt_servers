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

# Server Metrics 2026-03-13 09:26:10 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 93166.1 (25h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 365007
telemt_connections_bad_total 3189
telemt_handshake_timeouts_total 7824
telemt_upstream_connect_attempt_total 23538
telemt_upstream_connect_success_total 23429
telemt_upstream_connect_fail_total 109
telemt_upstream_connect_attempts_per_request{bucket="1"} 23538
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10566
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12815
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 109
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1715
telemt_me_reconnect_attempts_total 22263
telemt_me_reconnect_success_total 18751
telemt_me_reader_eof_total 20037
telemt_me_idle_close_by_peer_total 20036
telemt_me_route_drop_no_conn_total 114767
telemt_me_route_drop_channel_closed_total 21
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 312794
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 993
telemt_desync_full_logged_total 370
telemt_desync_suppressed_total 623
telemt_desync_frames_bucket_total{bucket="1_2"} 208
telemt_desync_frames_bucket_total{bucket="3_10"} 362
telemt_desync_frames_bucket_total{bucket="gt_10"} 423
telemt_pool_swap_total 84
telemt_me_writer_removed_unexpected_total 19058
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 18735
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 307
telemt_user_connections_total{user="hello"} 312486
telemt_user_connections_current{user="hello"} 358
telemt_user_octets_from_client{user="hello"} 5098423776 (4.75 GB)
telemt_user_octets_to_client{user="hello"} 139894154076 (130.29 GB)
telemt_user_unique_ips_current{user="hello"} 105
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 93059.0 (25h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 166853
telemt_connections_bad_total 1541
telemt_handshake_timeouts_total 1283
telemt_upstream_connect_attempt_total 46410
telemt_upstream_connect_success_total 45779
telemt_upstream_connect_fail_total 631
telemt_upstream_connect_attempts_per_request{bucket="1"} 46410
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26480
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18783
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 516
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 631
telemt_me_keepalive_timeout_total 709
telemt_me_reconnect_attempts_total 80001
telemt_me_reconnect_success_total 24625
telemt_me_reader_eof_total 27093
telemt_me_idle_close_by_peer_total 27093
telemt_me_route_drop_no_conn_total 63802
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 140528
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
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 26559
telemt_me_refill_failed_total 1728
telemt_me_writer_restored_same_endpoint_total 24610
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1934
telemt_user_connections_total{user="hello"} 157016
telemt_user_connections_current{user="hello"} 157
telemt_user_octets_from_client{user="hello"} 1641365068 (1.53 GB)
telemt_user_octets_to_client{user="hello"} 50751370223 (47.27 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 93022.7 (25h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 203604
telemt_connections_bad_total 2007
telemt_handshake_timeouts_total 4147
telemt_upstream_connect_attempt_total 25163
telemt_upstream_connect_success_total 25160
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 25163
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11563
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13572
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 639
telemt_me_reconnect_attempts_total 21650
telemt_me_reconnect_success_total 20461
telemt_me_reader_eof_total 21950
telemt_me_idle_close_by_peer_total 21950
telemt_me_route_drop_no_conn_total 76875
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 189967
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 63
telemt_desync_full_logged_total 31
telemt_desync_suppressed_total 32
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 21
telemt_desync_frames_bucket_total{bucket="gt_10"} 39
telemt_pool_swap_total 86
telemt_me_writer_removed_unexpected_total 20686
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 20441
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 225
telemt_user_connections_total{user="hello"} 189892
telemt_user_connections_current{user="hello"} 158
telemt_user_octets_from_client{user="hello"} 7842275252 (7.30 GB)
telemt_user_octets_to_client{user="hello"} 79219182828 (73.78 GB)
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 92998.2 (25h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 290036
telemt_connections_bad_total 13664
telemt_handshake_timeouts_total 2140
telemt_upstream_connect_attempt_total 38245
telemt_upstream_connect_success_total 28239
telemt_upstream_connect_fail_total 10006
telemt_upstream_connect_attempts_per_request{bucket="1"} 38245
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14117
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13927
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 186
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10006
telemt_me_keepalive_timeout_total 3423
telemt_me_reconnect_attempts_total 77358
telemt_me_reconnect_success_total 20723
telemt_me_reader_eof_total 23132
telemt_me_idle_close_by_peer_total 23125
telemt_me_route_drop_no_conn_total 104718
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 247783
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 910
telemt_desync_full_logged_total 267
telemt_desync_suppressed_total 643
telemt_desync_frames_bucket_total{bucket="1_2"} 230
telemt_desync_frames_bucket_total{bucket="3_10"} 340
telemt_desync_frames_bucket_total{bucket="gt_10"} 340
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 22754
telemt_me_refill_failed_total 1765
telemt_me_writer_restored_same_endpoint_total 20713
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 2031
telemt_user_connections_total{user="hello"} 250506
telemt_user_connections_current{user="hello"} 241
telemt_user_octets_from_client{user="hello"} 5514921546 (5.14 GB)
telemt_user_octets_to_client{user="hello"} 94657392337 (88.16 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 75
telemt_user_unique_ips_recent_window{user="hello"} 45
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 43169.7 (11h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 56296
telemt_connections_bad_total 8699
telemt_handshake_timeouts_total 471
telemt_upstream_connect_attempt_total 14933
telemt_upstream_connect_success_total 14787
telemt_upstream_connect_fail_total 146
telemt_upstream_connect_attempts_per_request{bucket="1"} 14933
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6491
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8245
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 146
telemt_me_keepalive_timeout_total 357
telemt_me_reconnect_attempts_total 14862
telemt_me_reconnect_success_total 12637
telemt_me_reader_eof_total 13461
telemt_me_idle_close_by_peer_total 13461
telemt_me_route_drop_no_conn_total 17136
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 45577
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 76
telemt_desync_full_logged_total 13
telemt_desync_suppressed_total 63
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 32
telemt_desync_frames_bucket_total{bucket="gt_10"} 37
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 12818
telemt_me_refill_failed_total 68
telemt_me_writer_restored_same_endpoint_total 12619
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 181
telemt_user_connections_total{user="hello"} 45572
telemt_user_connections_current{user="hello"} 90
telemt_user_octets_from_client{user="hello"} 335062312 (319.54 MB)
telemt_user_octets_to_client{user="hello"} 12415618660 (11.56 GB)
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 92954.9 (25h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 500099
telemt_connections_bad_total 13782
telemt_handshake_timeouts_total 5277
telemt_upstream_connect_attempt_total 19743
telemt_upstream_connect_success_total 19637
telemt_upstream_connect_fail_total 106
telemt_upstream_connect_attempts_per_request{bucket="1"} 19743
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9201
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10411
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 106
telemt_me_keepalive_timeout_total 1541
telemt_me_reconnect_attempts_total 18650
telemt_me_reconnect_success_total 15004
telemt_me_reader_eof_total 16099
telemt_me_idle_close_by_peer_total 16096
telemt_me_route_drop_no_conn_total 261188
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 490328
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 398
telemt_desync_full_logged_total 152
telemt_desync_suppressed_total 246
telemt_desync_frames_bucket_total{bucket="1_2"} 94
telemt_desync_frames_bucket_total{bucket="3_10"} 143
telemt_desync_frames_bucket_total{bucket="gt_10"} 161
telemt_pool_swap_total 87
telemt_me_writer_removed_unexpected_total 15312
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 14997
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 308
telemt_user_connections_total{user="hello"} 463419
telemt_user_connections_current{user="hello"} 449
telemt_user_octets_from_client{user="hello"} 8459222260 (7.88 GB)
telemt_user_octets_to_client{user="hello"} 261656044924 (243.69 GB)
telemt_user_unique_ips_current{user="hello"} 156
telemt_user_unique_ips_recent_window{user="hello"} 66
```