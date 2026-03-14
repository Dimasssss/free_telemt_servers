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

# Server Metrics 2026-03-14 10:56:46 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 185006.1 (51h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 724257
telemt_connections_bad_total 34239
telemt_handshake_timeouts_total 13914
telemt_upstream_connect_attempt_total 47138
telemt_upstream_connect_success_total 46903
telemt_upstream_connect_fail_total 235
telemt_upstream_connect_attempts_per_request{bucket="1"} 47138
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21415
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25336
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 152
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 235
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 6078
telemt_me_reconnect_attempts_total 43066
telemt_me_reconnect_success_total 37304
telemt_me_reader_eof_total 39889
telemt_me_idle_close_by_peer_total 39888
telemt_me_route_drop_no_conn_total 239478
telemt_me_route_drop_channel_closed_total 38
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 620660
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2494
telemt_desync_full_logged_total 830
telemt_desync_suppressed_total 1664
telemt_desync_frames_bucket_total{bucket="1_2"} 532
telemt_desync_frames_bucket_total{bucket="3_10"} 926
telemt_desync_frames_bucket_total{bucket="gt_10"} 1036
telemt_pool_swap_total 168
telemt_me_writer_removed_unexpected_total 37881
telemt_me_refill_failed_total 173
telemt_me_writer_restored_same_endpoint_total 37284
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 577
telemt_user_connections_total{user="hello"} 620540
telemt_user_connections_current{user="hello"} 436
telemt_user_octets_from_client{user="hello"} 17499934242 (16.30 GB)
telemt_user_octets_to_client{user="hello"} 297482510312 (277.05 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 118
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 184899.4 (51h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 360967
telemt_connections_bad_total 2826
telemt_handshake_timeouts_total 3288
telemt_upstream_connect_attempt_total 154818
telemt_upstream_connect_success_total 153456
telemt_upstream_connect_fail_total 1362
telemt_upstream_connect_attempts_per_request{bucket="1"} 154818
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 111909
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39082
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2464
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1362
telemt_me_keepalive_timeout_total 5488
telemt_me_reconnect_attempts_total 190179
telemt_me_reconnect_success_total 40926
telemt_me_reader_eof_total 46666
telemt_me_idle_close_by_peer_total 46666
telemt_me_route_drop_no_conn_total 124493
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 237566
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
telemt_me_writer_removed_unexpected_total 45984
telemt_me_refill_failed_total 4657
telemt_me_writer_restored_same_endpoint_total 40909
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 5058
telemt_user_connections_total{user="hello"} 340670
telemt_user_connections_current{user="hello"} 148
telemt_user_octets_from_client{user="hello"} 3477196187 (3.24 GB)
telemt_user_octets_to_client{user="hello"} 108463077875 (101.01 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 184863.0 (51h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 417494
telemt_connections_bad_total 3282
telemt_handshake_timeouts_total 35881
telemt_upstream_connect_attempt_total 49122
telemt_upstream_connect_success_total 49113
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 49122
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22494
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26548
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3917
telemt_me_reconnect_attempts_total 41153
telemt_me_reconnect_success_total 39843
telemt_me_reader_eof_total 42817
telemt_me_idle_close_by_peer_total 42817
telemt_me_route_drop_no_conn_total 151741
telemt_me_route_drop_channel_closed_total 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 363543
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
telemt_me_writer_removed_unexpected_total 40323
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 39822
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 480
telemt_user_connections_total{user="hello"} 363269
telemt_user_connections_current{user="hello"} 126
telemt_user_octets_from_client{user="hello"} 14009837560 (13.05 GB)
telemt_user_octets_to_client{user="hello"} 160025675592 (149.04 GB)
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 184838.2 (51h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 528491
telemt_connections_bad_total 16724
telemt_handshake_timeouts_total 5261
telemt_upstream_connect_attempt_total 79664
telemt_upstream_connect_success_total 68976
telemt_upstream_connect_fail_total 10688
telemt_upstream_connect_attempts_per_request{bucket="1"} 79664
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40174
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28435
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 358
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10688
telemt_me_keepalive_timeout_total 5679
telemt_me_reconnect_attempts_total 154141
telemt_me_reconnect_success_total 40719
telemt_me_reader_eof_total 45561
telemt_me_idle_close_by_peer_total 45553
telemt_me_route_drop_no_conn_total 191454
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 452746
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
telemt_me_writer_removed_unexpected_total 44725
telemt_me_refill_failed_total 3536
telemt_me_writer_restored_same_endpoint_total 40709
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 4006
telemt_user_connections_total{user="hello"} 471612
telemt_user_connections_current{user="hello"} 191
telemt_user_octets_from_client{user="hello"} 10078392359 (9.39 GB)
telemt_user_octets_to_client{user="hello"} 193938755116 (180.62 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 64
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 135009.7 (37h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 226688
telemt_connections_bad_total 35416
telemt_handshake_timeouts_total 2016
telemt_upstream_connect_attempt_total 47511
telemt_upstream_connect_success_total 47041
telemt_upstream_connect_fail_total 470
telemt_upstream_connect_attempts_per_request{bucket="1"} 47511
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23481
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23403
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 157
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 470
telemt_me_keepalive_timeout_total 2839
telemt_me_reconnect_attempts_total 51330
telemt_me_reconnect_success_total 35446
telemt_me_reader_eof_total 37918
telemt_me_idle_close_by_peer_total 37918
telemt_me_route_drop_no_conn_total 68742
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 178281
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
telemt_me_writer_removed_unexpected_total 36270
telemt_me_refill_failed_total 492
telemt_me_writer_restored_same_endpoint_total 35428
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 824
telemt_user_connections_total{user="hello"} 183038
telemt_user_connections_current{user="hello"} 89
telemt_user_octets_from_client{user="hello"} 2697628749 (2.51 GB)
telemt_user_octets_to_client{user="hello"} 84757528911 (78.94 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 184794.5 (51h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1073254
telemt_connections_bad_total 37352
telemt_handshake_timeouts_total 26977
telemt_upstream_connect_attempt_total 38670
telemt_upstream_connect_success_total 38467
telemt_upstream_connect_fail_total 203
telemt_upstream_connect_attempts_per_request{bucket="1"} 38670
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18218
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20208
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 203
telemt_me_keepalive_timeout_total 4882
telemt_me_reconnect_attempts_total 34005
telemt_me_reconnect_success_total 29315
telemt_me_reader_eof_total 31433
telemt_me_idle_close_by_peer_total 31430
telemt_me_route_drop_no_conn_total 503028
telemt_me_route_drop_channel_closed_total 26
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 995021
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
telemt_me_writer_removed_unexpected_total 29829
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 29308
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 514
telemt_user_connections_total{user="hello"} 967608
telemt_user_connections_current{user="hello"} 436
telemt_user_octets_from_client{user="hello"} 18122243792 (16.88 GB)
telemt_user_octets_to_client{user="hello"} 486230939168 (452.84 GB)
telemt_user_unique_ips_current{user="hello"} 174
telemt_user_unique_ips_recent_window{user="hello"} 64
```