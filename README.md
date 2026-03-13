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

# Server Metrics 2026-03-13 07:38:37 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 86713.6 (24h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 333656
telemt_connections_bad_total 3167
telemt_handshake_timeouts_total 7481
telemt_upstream_connect_attempt_total 21800
telemt_upstream_connect_success_total 21700
telemt_upstream_connect_fail_total 100
telemt_upstream_connect_attempts_per_request{bucket="1"} 21800
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9763
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11889
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 100
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1655
telemt_me_reconnect_attempts_total 20844
telemt_me_reconnect_success_total 17339
telemt_me_reader_eof_total 18548
telemt_me_idle_close_by_peer_total 18547
telemt_me_route_drop_no_conn_total 104434
telemt_me_route_drop_channel_closed_total 18
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 283629
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 945
telemt_desync_full_logged_total 350
telemt_desync_suppressed_total 595
telemt_desync_frames_bucket_total{bucket="1_2"} 188
telemt_desync_frames_bucket_total{bucket="3_10"} 345
telemt_desync_frames_bucket_total{bucket="gt_10"} 412
telemt_pool_swap_total 79
telemt_me_writer_removed_unexpected_total 17633
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 17323
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 294
telemt_user_connections_total{user="hello"} 283327
telemt_user_connections_current{user="hello"} 352
telemt_user_octets_from_client{user="hello"} 4725384348 (4.40 GB)
telemt_user_octets_to_client{user="hello"} 132182228852 (123.10 GB)
telemt_user_unique_ips_current{user="hello"} 105
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 86606.6 (24h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 151741
telemt_connections_bad_total 1477
telemt_handshake_timeouts_total 1177
telemt_upstream_connect_attempt_total 44624
telemt_upstream_connect_success_total 44022
telemt_upstream_connect_fail_total 602
telemt_upstream_connect_attempts_per_request{bucket="1"} 44624
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25752
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17759
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 511
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 602
telemt_me_keepalive_timeout_total 669
telemt_me_reconnect_attempts_total 75608
telemt_me_reconnect_success_total 23182
telemt_me_reader_eof_total 25511
telemt_me_idle_close_by_peer_total 25511
telemt_me_route_drop_no_conn_total 57084
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 127022
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 18
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
telemt_me_writer_removed_unexpected_total 25010
telemt_me_refill_failed_total 1636
telemt_me_writer_restored_same_endpoint_total 23167
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1828
telemt_user_connections_total{user="hello"} 143514
telemt_user_connections_current{user="hello"} 165
telemt_user_octets_from_client{user="hello"} 1486664004 (1.38 GB)
telemt_user_octets_to_client{user="hello"} 46081568887 (42.92 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 86570.2 (24h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 183876
telemt_connections_bad_total 1971
telemt_handshake_timeouts_total 3079
telemt_upstream_connect_attempt_total 23560
telemt_upstream_connect_success_total 23558
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 23560
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10843
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12692
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 563
telemt_me_reconnect_attempts_total 20354
telemt_me_reconnect_success_total 19177
telemt_me_reader_eof_total 20570
telemt_me_idle_close_by_peer_total 20570
telemt_me_route_drop_no_conn_total 70979
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 171998
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
telemt_pool_swap_total 80
telemt_me_writer_removed_unexpected_total 19386
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 19157
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 209
telemt_user_connections_total{user="hello"} 171927
telemt_user_connections_current{user="hello"} 156
telemt_user_octets_from_client{user="hello"} 3090228576 (2.88 GB)
telemt_user_octets_to_client{user="hello"} 74376069620 (69.27 GB)
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 86545.9 (24h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 264934
telemt_connections_bad_total 13616
telemt_handshake_timeouts_total 2017
telemt_upstream_connect_attempt_total 36198
telemt_upstream_connect_success_total 26247
telemt_upstream_connect_fail_total 9951
telemt_upstream_connect_attempts_per_request{bucket="1"} 36198
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13138
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12923
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 177
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9951
telemt_me_keepalive_timeout_total 3365
telemt_me_reconnect_attempts_total 70588
telemt_me_reconnect_success_total 19047
telemt_me_reader_eof_total 21265
telemt_me_idle_close_by_peer_total 21258
telemt_me_route_drop_no_conn_total 95542
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 224217
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 776
telemt_desync_full_logged_total 224
telemt_desync_suppressed_total 552
telemt_desync_frames_bucket_total{bucket="1_2"} 187
telemt_desync_frames_bucket_total{bucket="3_10"} 293
telemt_desync_frames_bucket_total{bucket="gt_10"} 296
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 20903
telemt_me_refill_failed_total 1606
telemt_me_writer_restored_same_endpoint_total 19037
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1856
telemt_user_connections_total{user="hello"} 226946
telemt_user_connections_current{user="hello"} 194
telemt_user_octets_from_client{user="hello"} 5214515006 (4.86 GB)
telemt_user_octets_to_client{user="hello"} 86758972097 (80.80 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 36717.5 (10h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 45003
telemt_connections_bad_total 7534
telemt_handshake_timeouts_total 401
telemt_upstream_connect_attempt_total 12472
telemt_upstream_connect_success_total 12345
telemt_upstream_connect_fail_total 127
telemt_upstream_connect_attempts_per_request{bucket="1"} 12472
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5369
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6933
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 127
telemt_me_keepalive_timeout_total 297
telemt_me_reconnect_attempts_total 11481
telemt_me_reconnect_success_total 10513
telemt_me_reader_eof_total 11200
telemt_me_idle_close_by_peer_total 11200
telemt_me_route_drop_no_conn_total 12956
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 35848
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 35
telemt_desync_full_logged_total 3
telemt_desync_suppressed_total 32
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 11
telemt_desync_frames_bucket_total{bucket="gt_10"} 20
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 10636
telemt_me_refill_failed_total 29
telemt_me_writer_restored_same_endpoint_total 10495
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 123
telemt_user_connections_total{user="hello"} 35847
telemt_user_connections_current{user="hello"} 65
telemt_user_octets_from_client{user="hello"} 261940300 (249.81 MB)
telemt_user_octets_to_client{user="hello"} 10986464576 (10.23 GB)
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 86502.3 (24h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 451951
telemt_connections_bad_total 11666
telemt_handshake_timeouts_total 3594
telemt_upstream_connect_attempt_total 18372
telemt_upstream_connect_success_total 18273
telemt_upstream_connect_fail_total 99
telemt_upstream_connect_attempts_per_request{bucket="1"} 18372
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8549
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9699
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 99
telemt_me_keepalive_timeout_total 1503
telemt_me_reconnect_attempts_total 17594
telemt_me_reconnect_success_total 13953
telemt_me_reader_eof_total 14986
telemt_me_idle_close_by_peer_total 14983
telemt_me_route_drop_no_conn_total 208682
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 436813
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 363
telemt_desync_full_logged_total 140
telemt_desync_suppressed_total 223
telemt_desync_frames_bucket_total{bucket="1_2"} 87
telemt_desync_frames_bucket_total{bucket="3_10"} 130
telemt_desync_frames_bucket_total{bucket="gt_10"} 146
telemt_pool_swap_total 82
telemt_me_writer_removed_unexpected_total 14244
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 13946
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 291
telemt_user_connections_total{user="hello"} 421195
telemt_user_connections_current{user="hello"} 407
telemt_user_octets_from_client{user="hello"} 7822407872 (7.29 GB)
telemt_user_octets_to_client{user="hello"} 243990056904 (227.23 GB)
telemt_user_unique_ips_current{user="hello"} 147
telemt_user_unique_ips_recent_window{user="hello"} 62
```