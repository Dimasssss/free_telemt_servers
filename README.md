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

# Server Metrics 2026-03-14 11:01:51 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 185311.1 (51h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 725841
telemt_connections_bad_total 34239
telemt_handshake_timeouts_total 13929
telemt_upstream_connect_attempt_total 47170
telemt_upstream_connect_success_total 46935
telemt_upstream_connect_fail_total 235
telemt_upstream_connect_attempts_per_request{bucket="1"} 47170
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21432
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25351
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 152
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 235
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 6079
telemt_me_reconnect_attempts_total 43098
telemt_me_reconnect_success_total 37336
telemt_me_reader_eof_total 39922
telemt_me_idle_close_by_peer_total 39921
telemt_me_route_drop_no_conn_total 240017
telemt_me_route_drop_channel_closed_total 38
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 622101
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2516
telemt_desync_full_logged_total 836
telemt_desync_suppressed_total 1680
telemt_desync_frames_bucket_total{bucket="1_2"} 537
telemt_desync_frames_bucket_total{bucket="3_10"} 936
telemt_desync_frames_bucket_total{bucket="gt_10"} 1043
telemt_pool_swap_total 168
telemt_me_writer_removed_unexpected_total 37913
telemt_me_refill_failed_total 173
telemt_me_writer_restored_same_endpoint_total 37316
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 577
telemt_user_connections_total{user="hello"} 621983
telemt_user_connections_current{user="hello"} 444
telemt_user_octets_from_client{user="hello"} 17526253502 (16.32 GB)
telemt_user_octets_to_client{user="hello"} 298355267864 (277.86 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 127
telemt_user_unique_ips_recent_window{user="hello"} 54
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 185204.6 (51h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 361674
telemt_connections_bad_total 2836
telemt_handshake_timeouts_total 3288
telemt_upstream_connect_attempt_total 154941
telemt_upstream_connect_success_total 153579
telemt_upstream_connect_fail_total 1362
telemt_upstream_connect_attempts_per_request{bucket="1"} 154941
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 111933
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39179
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2466
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1362
telemt_me_keepalive_timeout_total 5492
telemt_me_reconnect_attempts_total 190302
telemt_me_reconnect_success_total 41050
telemt_me_reader_eof_total 46790
telemt_me_idle_close_by_peer_total 46790
telemt_me_route_drop_no_conn_total 124738
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 238258
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 45
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 33
telemt_desync_full_logged_total 11
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 19
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 46108
telemt_me_refill_failed_total 4657
telemt_me_writer_restored_same_endpoint_total 41033
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 5058
telemt_user_connections_total{user="hello"} 341361
telemt_user_connections_current{user="hello"} 151
telemt_user_octets_from_client{user="hello"} 3481201051 (3.24 GB)
telemt_user_octets_to_client{user="hello"} 108760845303 (101.29 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 185168.1 (51h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 418067
telemt_connections_bad_total 3282
telemt_handshake_timeouts_total 35883
telemt_upstream_connect_attempt_total 49215
telemt_upstream_connect_success_total 49206
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 49215
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22540
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26595
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3917
telemt_me_reconnect_attempts_total 41246
telemt_me_reconnect_success_total 39937
telemt_me_reader_eof_total 42910
telemt_me_idle_close_by_peer_total 42910
telemt_me_route_drop_no_conn_total 151985
telemt_me_route_drop_channel_closed_total 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 364078
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 138
telemt_desync_full_logged_total 63
telemt_desync_suppressed_total 75
telemt_desync_frames_bucket_total{bucket="1_2"} 14
telemt_desync_frames_bucket_total{bucket="3_10"} 48
telemt_desync_frames_bucket_total{bucket="gt_10"} 76
telemt_pool_swap_total 173
telemt_me_writer_removed_unexpected_total 40416
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 39916
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 479
telemt_user_connections_total{user="hello"} 363802
telemt_user_connections_current{user="hello"} 159
telemt_user_octets_from_client{user="hello"} 14187232084 (13.21 GB)
telemt_user_octets_to_client{user="hello"} 160297260480 (149.29 GB)
telemt_user_unique_ips_current{user="hello"} 65
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 185144.0 (51h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 529493
telemt_connections_bad_total 16724
telemt_handshake_timeouts_total 5263
telemt_upstream_connect_attempt_total 79729
telemt_upstream_connect_success_total 69041
telemt_upstream_connect_fail_total 10688
telemt_upstream_connect_attempts_per_request{bucket="1"} 79729
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40205
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28465
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 362
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10688
telemt_me_keepalive_timeout_total 5686
telemt_me_reconnect_attempts_total 154206
telemt_me_reconnect_success_total 40784
telemt_me_reader_eof_total 45627
telemt_me_idle_close_by_peer_total 45619
telemt_me_route_drop_no_conn_total 191880
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 453672
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 36
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2031
telemt_desync_full_logged_total 605
telemt_desync_suppressed_total 1426
telemt_desync_frames_bucket_total{bucket="1_2"} 479
telemt_desync_frames_bucket_total{bucket="3_10"} 776
telemt_desync_frames_bucket_total{bucket="gt_10"} 776
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 44791
telemt_me_refill_failed_total 3536
telemt_me_writer_restored_same_endpoint_total 40774
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 4007
telemt_user_connections_total{user="hello"} 472538
telemt_user_connections_current{user="hello"} 191
telemt_user_octets_from_client{user="hello"} 10085511027 (9.39 GB)
telemt_user_octets_to_client{user="hello"} 194158205408 (180.82 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 135315.3 (37h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 227378
telemt_connections_bad_total 35596
telemt_handshake_timeouts_total 2016
telemt_upstream_connect_attempt_total 47630
telemt_upstream_connect_success_total 47157
telemt_upstream_connect_fail_total 473
telemt_upstream_connect_attempts_per_request{bucket="1"} 47630
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23538
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23462
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 157
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 473
telemt_me_keepalive_timeout_total 2861
telemt_me_reconnect_attempts_total 51403
telemt_me_reconnect_success_total 35519
telemt_me_reader_eof_total 38007
telemt_me_idle_close_by_peer_total 38007
telemt_me_route_drop_no_conn_total 68978
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 178773
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 770
telemt_desync_full_logged_total 190
telemt_desync_suppressed_total 580
telemt_desync_frames_bucket_total{bucket="1_2"} 127
telemt_desync_frames_bucket_total{bucket="3_10"} 366
telemt_desync_frames_bucket_total{bucket="gt_10"} 277
telemt_pool_swap_total 101
telemt_me_writer_removed_unexpected_total 36345
telemt_me_refill_failed_total 492
telemt_me_writer_restored_same_endpoint_total 35501
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 826
telemt_user_connections_total{user="hello"} 183529
telemt_user_connections_current{user="hello"} 96
telemt_user_octets_from_client{user="hello"} 2703506229 (2.52 GB)
telemt_user_octets_to_client{user="hello"} 84847792299 (79.02 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 185100.2 (51h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1075407
telemt_connections_bad_total 37353
telemt_handshake_timeouts_total 26990
telemt_upstream_connect_attempt_total 38709
telemt_upstream_connect_success_total 38506
telemt_upstream_connect_fail_total 203
telemt_upstream_connect_attempts_per_request{bucket="1"} 38709
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18236
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20229
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 203
telemt_me_keepalive_timeout_total 4891
telemt_me_reconnect_attempts_total 34044
telemt_me_reconnect_success_total 29354
telemt_me_reader_eof_total 31473
telemt_me_idle_close_by_peer_total 31470
telemt_me_route_drop_no_conn_total 503931
telemt_me_route_drop_channel_closed_total 26
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 997080
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 807
telemt_desync_full_logged_total 267
telemt_desync_suppressed_total 540
telemt_desync_frames_bucket_total{bucket="1_2"} 260
telemt_desync_frames_bucket_total{bucket="3_10"} 268
telemt_desync_frames_bucket_total{bucket="gt_10"} 279
telemt_pool_swap_total 172
telemt_me_writer_removed_unexpected_total 29868
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 29347
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 514
telemt_user_connections_total{user="hello"} 969665
telemt_user_connections_current{user="hello"} 497
telemt_user_octets_from_client{user="hello"} 18144305104 (16.90 GB)
telemt_user_octets_to_client{user="hello"} 487582822512 (454.10 GB)
telemt_user_unique_ips_current{user="hello"} 174
telemt_user_unique_ips_recent_window{user="hello"} 65
```