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

# Server Metrics 2026-03-14 08:44:31 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 177071.1 (49h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 682586
telemt_connections_bad_total 32575
telemt_handshake_timeouts_total 13320
telemt_upstream_connect_attempt_total 44957
telemt_upstream_connect_success_total 44728
telemt_upstream_connect_fail_total 229
telemt_upstream_connect_attempts_per_request{bucket="1"} 44957
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20483
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24093
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 152
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 229
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 5781
telemt_me_reconnect_attempts_total 40233
telemt_me_reconnect_success_total 35535
telemt_me_reader_eof_total 37991
telemt_me_idle_close_by_peer_total 37990
telemt_me_route_drop_no_conn_total 225584
telemt_me_route_drop_channel_closed_total 32
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 582883
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2244
telemt_desync_full_logged_total 763
telemt_desync_suppressed_total 1481
telemt_desync_frames_bucket_total{bucket="1_2"} 486
telemt_desync_frames_bucket_total{bucket="3_10"} 821
telemt_desync_frames_bucket_total{bucket="gt_10"} 937
telemt_pool_swap_total 163
telemt_me_writer_removed_unexpected_total 36061
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 35515
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 526
telemt_user_connections_total{user="hello"} 582766
telemt_user_connections_current{user="hello"} 415
telemt_user_octets_from_client{user="hello"} 16997126314 (15.83 GB)
telemt_user_octets_to_client{user="hello"} 279818815672 (260.60 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 122
telemt_user_unique_ips_recent_window{user="hello"} 53
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 176963.9 (49h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 343618
telemt_connections_bad_total 2784
telemt_handshake_timeouts_total 3028
telemt_upstream_connect_attempt_total 152423
telemt_upstream_connect_success_total 151105
telemt_upstream_connect_fail_total 1318
telemt_upstream_connect_attempts_per_request{bucket="1"} 152423
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 110784
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37882
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2438
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1318
telemt_me_keepalive_timeout_total 5335
telemt_me_reconnect_attempts_total 180454
telemt_me_reconnect_success_total 38985
telemt_me_reader_eof_total 44457
telemt_me_idle_close_by_peer_total 44457
telemt_me_route_drop_no_conn_total 115506
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 221053
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 43
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
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 43783
telemt_me_refill_failed_total 4414
telemt_me_writer_restored_same_endpoint_total 38968
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 4798
telemt_user_connections_total{user="hello"} 324159
telemt_user_connections_current{user="hello"} 101
telemt_user_octets_from_client{user="hello"} 3355657179 (3.13 GB)
telemt_user_octets_to_client{user="hello"} 104861648263 (97.66 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 176927.8 (49h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 401331
telemt_connections_bad_total 3198
telemt_handshake_timeouts_total 35577
telemt_upstream_connect_attempt_total 46886
telemt_upstream_connect_success_total 46877
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 46886
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21459
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25350
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3514
telemt_me_reconnect_attempts_total 39314
telemt_me_reconnect_success_total 38020
telemt_me_reader_eof_total 40849
telemt_me_idle_close_by_peer_total 40849
telemt_me_route_drop_no_conn_total 145025
telemt_me_route_drop_channel_closed_total 22
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 348420
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 123
telemt_desync_full_logged_total 55
telemt_desync_suppressed_total 68
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 41
telemt_desync_frames_bucket_total{bucket="gt_10"} 69
telemt_pool_swap_total 166
telemt_me_writer_removed_unexpected_total 38482
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 37999
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 462
telemt_user_connections_total{user="hello"} 348181
telemt_user_connections_current{user="hello"} 148
telemt_user_octets_from_client{user="hello"} 13682110332 (12.74 GB)
telemt_user_octets_to_client{user="hello"} 147000299328 (136.90 GB)
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 176903.1 (49h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 503577
telemt_connections_bad_total 16286
telemt_handshake_timeouts_total 4583
telemt_upstream_connect_attempt_total 77141
telemt_upstream_connect_success_total 66504
telemt_upstream_connect_fail_total 10637
telemt_upstream_connect_attempts_per_request{bucket="1"} 77141
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39048
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27101
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 346
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10637
telemt_me_keepalive_timeout_total 5486
telemt_me_reconnect_attempts_total 149782
telemt_me_reconnect_success_total 38662
telemt_me_reader_eof_total 43367
telemt_me_idle_close_by_peer_total 43359
telemt_me_route_drop_no_conn_total 182715
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 430166
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 34
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1883
telemt_desync_full_logged_total 557
telemt_desync_suppressed_total 1326
telemt_desync_frames_bucket_total{bucket="1_2"} 443
telemt_desync_frames_bucket_total{bucket="3_10"} 729
telemt_desync_frames_bucket_total{bucket="gt_10"} 711
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 42576
telemt_me_refill_failed_total 3465
telemt_me_writer_restored_same_endpoint_total 38652
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3914
telemt_user_connections_total{user="hello"} 449047
telemt_user_connections_current{user="hello"} 203
telemt_user_octets_from_client{user="hello"} 9691231375 (9.03 GB)
telemt_user_octets_to_client{user="hello"} 186316752496 (173.52 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 127074.7 (35h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 209089
telemt_connections_bad_total 32022
telemt_handshake_timeouts_total 1769
telemt_upstream_connect_attempt_total 44841
telemt_upstream_connect_success_total 44409
telemt_upstream_connect_fail_total 432
telemt_upstream_connect_attempts_per_request{bucket="1"} 44841
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22221
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22044
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 144
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 432
telemt_me_keepalive_timeout_total 2572
telemt_me_reconnect_attempts_total 47901
telemt_me_reconnect_success_total 33183
telemt_me_reader_eof_total 35518
telemt_me_idle_close_by_peer_total 35518
telemt_me_route_drop_no_conn_total 62797
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 164716
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 718
telemt_desync_full_logged_total 174
telemt_desync_suppressed_total 544
telemt_desync_frames_bucket_total{bucket="1_2"} 121
telemt_desync_frames_bucket_total{bucket="3_10"} 340
telemt_desync_frames_bucket_total{bucket="gt_10"} 257
telemt_pool_swap_total 97
telemt_me_writer_removed_unexpected_total 33944
telemt_me_refill_failed_total 456
telemt_me_writer_restored_same_endpoint_total 33165
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 761
telemt_user_connections_total{user="hello"} 169478
telemt_user_connections_current{user="hello"} 69
telemt_user_octets_from_client{user="hello"} 2488109305 (2.32 GB)
telemt_user_octets_to_client{user="hello"} 80968094447 (75.41 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 176859.3 (49h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1018040
telemt_connections_bad_total 36348
telemt_handshake_timeouts_total 26374
telemt_upstream_connect_attempt_total 36869
telemt_upstream_connect_success_total 36673
telemt_upstream_connect_fail_total 196
telemt_upstream_connect_attempts_per_request{bucket="1"} 36869
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17274
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19358
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 196
telemt_me_keepalive_timeout_total 4762
telemt_me_reconnect_attempts_total 32608
telemt_me_reconnect_success_total 27925
telemt_me_reader_eof_total 29958
telemt_me_idle_close_by_peer_total 29955
telemt_me_route_drop_no_conn_total 478470
telemt_me_route_drop_channel_closed_total 25
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 943655
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 792
telemt_desync_full_logged_total 259
telemt_desync_suppressed_total 533
telemt_desync_frames_bucket_total{bucket="1_2"} 260
telemt_desync_frames_bucket_total{bucket="3_10"} 264
telemt_desync_frames_bucket_total{bucket="gt_10"} 268
telemt_pool_swap_total 167
telemt_me_writer_removed_unexpected_total 28422
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 27918
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 497
telemt_user_connections_total{user="hello"} 916283
telemt_user_connections_current{user="hello"} 380
telemt_user_octets_from_client{user="hello"} 15510709556 (14.45 GB)
telemt_user_octets_to_client{user="hello"} 457145836856 (425.75 GB)
telemt_user_unique_ips_current{user="hello"} 164
telemt_user_unique_ips_recent_window{user="hello"} 67
```