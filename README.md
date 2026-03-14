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

# Server Metrics 2026-03-14 10:51:40 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 184700.3 (51h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 722612
telemt_connections_bad_total 34239
telemt_handshake_timeouts_total 13890
telemt_upstream_connect_attempt_total 47084
telemt_upstream_connect_success_total 46849
telemt_upstream_connect_fail_total 235
telemt_upstream_connect_attempts_per_request{bucket="1"} 47084
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21387
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25310
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 152
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 235
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 6076
telemt_me_reconnect_attempts_total 43012
telemt_me_reconnect_success_total 37250
telemt_me_reader_eof_total 39834
telemt_me_idle_close_by_peer_total 39833
telemt_me_route_drop_no_conn_total 238889
telemt_me_route_drop_channel_closed_total 38
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 619131
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2471
telemt_desync_full_logged_total 825
telemt_desync_suppressed_total 1646
telemt_desync_frames_bucket_total{bucket="1_2"} 528
telemt_desync_frames_bucket_total{bucket="3_10"} 915
telemt_desync_frames_bucket_total{bucket="gt_10"} 1028
telemt_pool_swap_total 168
telemt_me_writer_removed_unexpected_total 37827
telemt_me_refill_failed_total 173
telemt_me_writer_restored_same_endpoint_total 37230
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 577
telemt_user_connections_total{user="hello"} 619010
telemt_user_connections_current{user="hello"} 402
telemt_user_octets_from_client{user="hello"} 17477544894 (16.28 GB)
telemt_user_octets_to_client{user="hello"} 296897367332 (276.51 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 117
telemt_user_unique_ips_recent_window{user="hello"} 51
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 184594.2 (51h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 360153
telemt_connections_bad_total 2825
telemt_handshake_timeouts_total 3254
telemt_upstream_connect_attempt_total 154673
telemt_upstream_connect_success_total 153311
telemt_upstream_connect_fail_total 1362
telemt_upstream_connect_attempts_per_request{bucket="1"} 154673
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 111871
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38976
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2463
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1362
telemt_me_keepalive_timeout_total 5484
telemt_me_reconnect_attempts_total 189089
telemt_me_reconnect_success_total 40797
telemt_me_reader_eof_total 46506
telemt_me_idle_close_by_peer_total 46506
telemt_me_route_drop_no_conn_total 124257
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 236770
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
telemt_me_writer_removed_unexpected_total 45824
telemt_me_refill_failed_total 4627
telemt_me_writer_restored_same_endpoint_total 40780
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 5027
telemt_user_connections_total{user="hello"} 339874
telemt_user_connections_current{user="hello"} 160
telemt_user_octets_from_client{user="hello"} 3473322899 (3.23 GB)
telemt_user_octets_to_client{user="hello"} 108260354015 (100.83 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 184557.7 (51h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 416886
telemt_connections_bad_total 3281
telemt_handshake_timeouts_total 35876
telemt_upstream_connect_attempt_total 48972
telemt_upstream_connect_success_total 48962
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 48971
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22415
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26478
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3917
telemt_me_reconnect_attempts_total 41042
telemt_me_reconnect_success_total 39735
telemt_me_reader_eof_total 42706
telemt_me_idle_close_by_peer_total 42706
telemt_me_route_drop_no_conn_total 151510
telemt_me_route_drop_channel_closed_total 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 362958
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
telemt_me_writer_removed_unexpected_total 40212
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 39714
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 477
telemt_user_connections_total{user="hello"} 362685
telemt_user_connections_current{user="hello"} 134
telemt_user_octets_from_client{user="hello"} 14002822068 (13.04 GB)
telemt_user_octets_to_client{user="hello"} 159598480004 (148.64 GB)
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 184533.3 (51h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 527447
telemt_connections_bad_total 16724
telemt_handshake_timeouts_total 5251
telemt_upstream_connect_attempt_total 79519
telemt_upstream_connect_success_total 68836
telemt_upstream_connect_fail_total 10682
telemt_upstream_connect_attempts_per_request{bucket="1"} 79518
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40104
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28368
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 355
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10682
telemt_me_keepalive_timeout_total 5677
telemt_me_reconnect_attempts_total 152923
telemt_me_reconnect_success_total 40622
telemt_me_reader_eof_total 45427
telemt_me_idle_close_by_peer_total 45419
telemt_me_route_drop_no_conn_total 191133
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 451794
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 36
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2030
telemt_desync_full_logged_total 604
telemt_desync_suppressed_total 1426
telemt_desync_frames_bucket_total{bucket="1_2"} 479
telemt_desync_frames_bucket_total{bucket="3_10"} 776
telemt_desync_frames_bucket_total{bucket="gt_10"} 775
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 44591
telemt_me_refill_failed_total 3501
telemt_me_writer_restored_same_endpoint_total 40612
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3969
telemt_user_connections_total{user="hello"} 470661
telemt_user_connections_current{user="hello"} 166
telemt_user_octets_from_client{user="hello"} 10064929555 (9.37 GB)
telemt_user_octets_to_client{user="hello"} 193795705228 (180.49 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 134704.7 (37h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 225892
telemt_connections_bad_total 35228
telemt_handshake_timeouts_total 2004
telemt_upstream_connect_attempt_total 47465
telemt_upstream_connect_success_total 46994
telemt_upstream_connect_fail_total 470
telemt_upstream_connect_attempts_per_request{bucket="1"} 47464
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23469
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23368
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 157
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 470
telemt_me_keepalive_timeout_total 2839
telemt_me_reconnect_attempts_total 51284
telemt_me_reconnect_success_total 35399
telemt_me_reader_eof_total 37872
telemt_me_idle_close_by_peer_total 37872
telemt_me_route_drop_no_conn_total 68455
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 177723
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 766
telemt_desync_full_logged_total 189
telemt_desync_suppressed_total 577
telemt_desync_frames_bucket_total{bucket="1_2"} 127
telemt_desync_frames_bucket_total{bucket="3_10"} 365
telemt_desync_frames_bucket_total{bucket="gt_10"} 274
telemt_pool_swap_total 100
telemt_me_writer_removed_unexpected_total 36224
telemt_me_refill_failed_total 492
telemt_me_writer_restored_same_endpoint_total 35381
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 825
telemt_user_connections_total{user="hello"} 182480
telemt_user_connections_current{user="hello"} 86
telemt_user_octets_from_client{user="hello"} 2693718969 (2.51 GB)
telemt_user_octets_to_client{user="hello"} 84565981011 (78.76 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 184489.6 (51h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1071190
telemt_connections_bad_total 37343
telemt_handshake_timeouts_total 26967
telemt_upstream_connect_attempt_total 38570
telemt_upstream_connect_success_total 38367
telemt_upstream_connect_fail_total 203
telemt_upstream_connect_attempts_per_request{bucket="1"} 38570
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18162
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20164
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 203
telemt_me_keepalive_timeout_total 4881
telemt_me_reconnect_attempts_total 33948
telemt_me_reconnect_success_total 29258
telemt_me_reader_eof_total 31362
telemt_me_idle_close_by_peer_total 31359
telemt_me_route_drop_no_conn_total 501906
telemt_me_route_drop_channel_closed_total 26
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 993056
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
telemt_pool_swap_total 171
telemt_me_writer_removed_unexpected_total 29772
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 29251
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 514
telemt_user_connections_total{user="hello"} 965644
telemt_user_connections_current{user="hello"} 456
telemt_user_octets_from_client{user="hello"} 18084562172 (16.84 GB)
telemt_user_octets_to_client{user="hello"} 484863723160 (451.56 GB)
telemt_user_unique_ips_current{user="hello"} 179
telemt_user_unique_ips_recent_window{user="hello"} 68
```