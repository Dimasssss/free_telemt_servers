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

# Server Metrics 2026-03-14 10:11:00 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 182259.6 (50h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 708167
telemt_connections_bad_total 33240
telemt_handshake_timeouts_total 13794
telemt_upstream_connect_attempt_total 46350
telemt_upstream_connect_success_total 46114
telemt_upstream_connect_fail_total 235
telemt_upstream_connect_attempts_per_request{bucket="1"} 46349
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21088
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24874
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 152
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 235
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 5943
telemt_me_reconnect_attempts_total 41357
telemt_me_reconnect_success_total 36651
telemt_me_reader_eof_total 39167
telemt_me_idle_close_by_peer_total 39166
telemt_me_route_drop_no_conn_total 234107
telemt_me_route_drop_channel_closed_total 33
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 606249
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2400
telemt_desync_full_logged_total 802
telemt_desync_suppressed_total 1598
telemt_desync_frames_bucket_total{bucket="1_2"} 513
telemt_desync_frames_bucket_total{bucket="3_10"} 883
telemt_desync_frames_bucket_total{bucket="gt_10"} 1004
telemt_pool_swap_total 166
telemt_me_writer_removed_unexpected_total 37194
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 36631
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 543
telemt_user_connections_total{user="hello"} 606127
telemt_user_connections_current{user="hello"} 394
telemt_user_octets_from_client{user="hello"} 17339763882 (16.15 GB)
telemt_user_octets_to_client{user="hello"} 288428501680 (268.62 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 121
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 182153.3 (50h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 355328
telemt_connections_bad_total 2822
telemt_handshake_timeouts_total 3139
telemt_upstream_connect_attempt_total 153788
telemt_upstream_connect_success_total 152441
telemt_upstream_connect_fail_total 1347
telemt_upstream_connect_attempts_per_request{bucket="1"} 153788
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 111520
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38469
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2451
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1347
telemt_me_keepalive_timeout_total 5450
telemt_me_reconnect_attempts_total 188342
telemt_me_reconnect_success_total 40055
telemt_me_reader_eof_total 45752
telemt_me_idle_close_by_peer_total 45752
telemt_me_route_drop_no_conn_total 121760
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 232259
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
telemt_me_writer_removed_unexpected_total 45069
telemt_me_refill_failed_total 4627
telemt_me_writer_restored_same_endpoint_total 40038
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 5014
telemt_user_connections_total{user="hello"} 335363
telemt_user_connections_current{user="hello"} 114
telemt_user_octets_from_client{user="hello"} 3441289943 (3.20 GB)
telemt_user_octets_to_client{user="hello"} 107246144959 (99.88 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 182116.9 (50h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 412177
telemt_connections_bad_total 3260
telemt_handshake_timeouts_total 35758
telemt_upstream_connect_attempt_total 48307
telemt_upstream_connect_success_total 48298
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 48307
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22113
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26116
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3773
telemt_me_reconnect_attempts_total 40472
telemt_me_reconnect_success_total 39169
telemt_me_reader_eof_total 42091
telemt_me_idle_close_by_peer_total 42091
telemt_me_route_drop_no_conn_total 149780
telemt_me_route_drop_channel_closed_total 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 358624
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 136
telemt_desync_full_logged_total 61
telemt_desync_suppressed_total 75
telemt_desync_frames_bucket_total{bucket="1_2"} 14
telemt_desync_frames_bucket_total{bucket="3_10"} 46
telemt_desync_frames_bucket_total{bucket="gt_10"} 76
telemt_pool_swap_total 171
telemt_me_writer_removed_unexpected_total 39639
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 39148
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 470
telemt_user_connections_total{user="hello"} 358353
telemt_user_connections_current{user="hello"} 140
telemt_user_octets_from_client{user="hello"} 13905252560 (12.95 GB)
telemt_user_octets_to_client{user="hello"} 158201501724 (147.34 GB)
telemt_user_unique_ips_current{user="hello"} 68
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 182092.6 (50h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 520008
telemt_connections_bad_total 16710
telemt_handshake_timeouts_total 5223
telemt_upstream_connect_attempt_total 78698
telemt_upstream_connect_success_total 68030
telemt_upstream_connect_fail_total 10668
telemt_upstream_connect_attempts_per_request{bucket="1"} 78698
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39736
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27935
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 350
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10668
telemt_me_keepalive_timeout_total 5625
telemt_me_reconnect_attempts_total 152212
telemt_me_reconnect_success_total 39915
telemt_me_reader_eof_total 44714
telemt_me_idle_close_by_peer_total 44706
telemt_me_route_drop_no_conn_total 188561
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 444861
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 36
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1992
telemt_desync_full_logged_total 590
telemt_desync_suppressed_total 1402
telemt_desync_frames_bucket_total{bucket="1_2"} 469
telemt_desync_frames_bucket_total{bucket="3_10"} 766
telemt_desync_frames_bucket_total{bucket="gt_10"} 757
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 43877
telemt_me_refill_failed_total 3501
telemt_me_writer_restored_same_endpoint_total 39905
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3962
telemt_user_connections_total{user="hello"} 463728
telemt_user_connections_current{user="hello"} 176
telemt_user_octets_from_client{user="hello"} 9967221415 (9.28 GB)
telemt_user_octets_to_client{user="hello"} 192343607128 (179.13 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 132264.1 (36h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 219622
telemt_connections_bad_total 33736
telemt_handshake_timeouts_total 1981
telemt_upstream_connect_attempt_total 46523
telemt_upstream_connect_success_total 46068
telemt_upstream_connect_fail_total 455
telemt_upstream_connect_attempts_per_request{bucket="1"} 46523
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23027
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22890
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 151
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 455
telemt_me_keepalive_timeout_total 2741
telemt_me_reconnect_attempts_total 50489
telemt_me_reconnect_success_total 34611
telemt_me_reader_eof_total 37040
telemt_me_idle_close_by_peer_total 37040
telemt_me_route_drop_no_conn_total 66506
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 173108
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 759
telemt_desync_full_logged_total 187
telemt_desync_suppressed_total 572
telemt_desync_frames_bucket_total{bucket="1_2"} 127
telemt_desync_frames_bucket_total{bucket="3_10"} 361
telemt_desync_frames_bucket_total{bucket="gt_10"} 271
telemt_pool_swap_total 99
telemt_me_writer_removed_unexpected_total 35424
telemt_me_refill_failed_total 492
telemt_me_writer_restored_same_endpoint_total 34593
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 813
telemt_user_connections_total{user="hello"} 177867
telemt_user_connections_current{user="hello"} 95
telemt_user_octets_from_client{user="hello"} 2657694461 (2.48 GB)
telemt_user_octets_to_client{user="hello"} 83279173563 (77.56 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 182048.7 (50h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1053780
telemt_connections_bad_total 36950
telemt_handshake_timeouts_total 26871
telemt_upstream_connect_attempt_total 38033
telemt_upstream_connect_success_total 37832
telemt_upstream_connect_fail_total 201
telemt_upstream_connect_attempts_per_request{bucket="1"} 38033
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17888
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19903
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 201
telemt_me_keepalive_timeout_total 4864
telemt_me_reconnect_attempts_total 33501
telemt_me_reconnect_success_total 28815
telemt_me_reader_eof_total 30897
telemt_me_idle_close_by_peer_total 30894
telemt_me_route_drop_no_conn_total 493344
telemt_me_route_drop_channel_closed_total 25
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 976751
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 806
telemt_desync_full_logged_total 266
telemt_desync_suppressed_total 540
telemt_desync_frames_bucket_total{bucket="1_2"} 260
telemt_desync_frames_bucket_total{bucket="3_10"} 268
telemt_desync_frames_bucket_total{bucket="gt_10"} 278
telemt_pool_swap_total 170
telemt_me_writer_removed_unexpected_total 29325
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 28808
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 510
telemt_user_connections_total{user="hello"} 949363
telemt_user_connections_current{user="hello"} 463
telemt_user_octets_from_client{user="hello"} 17830203944 (16.61 GB)
telemt_user_octets_to_client{user="hello"} 477156383336 (444.39 GB)
telemt_user_unique_ips_current{user="hello"} 181
telemt_user_unique_ips_recent_window{user="hello"} 70
```