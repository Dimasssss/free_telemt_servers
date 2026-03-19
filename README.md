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

## 4vps.su
- Локация: Польша, Варшава
- Тариф: PL-cx21
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 2 Gbit/s
- Цена в месяц: 770 RUB
- Оплачен до: 16 апреля
- Ссылка:
```bash
tg://proxy?server=s7.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

# Server Metrics 2026-03-19 09:58:27 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 43799.7 (12h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 945207
telemt_connections_bad_total 84107
telemt_connections_current 1542
telemt_connections_me_current 1542
telemt_handshake_timeouts_total 35169
telemt_upstream_connect_attempt_total 8310
telemt_upstream_connect_success_total 8165
telemt_upstream_connect_fail_total 145
telemt_upstream_connect_attempts_per_request{bucket="1"} 8310
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3954
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4208
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 145
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 89
telemt_me_reconnect_attempts_total 7131
telemt_me_reconnect_success_total 5973
telemt_me_reader_eof_total 6335
telemt_me_idle_close_by_peer_total 6334
telemt_me_seq_mismatch_total 10
telemt_me_route_drop_no_conn_total 319673
telemt_me_route_drop_channel_closed_total 127
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 727862
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 30
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4406
telemt_desync_full_logged_total 1334
telemt_desync_suppressed_total 3072
telemt_desync_frames_bucket_total{bucket="1_2"} 1472
telemt_desync_frames_bucket_total{bucket="3_10"} 1614
telemt_desync_frames_bucket_total{bucket="gt_10"} 1320
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 6084
telemt_me_refill_failed_total 35
telemt_me_writer_restored_same_endpoint_total 5953
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 111
telemt_user_connections_total{user="hello"} 722247
telemt_user_connections_current{user="hello"} 1542
telemt_user_octets_from_client{user="hello"} 11424291028 (10.64 GB)
telemt_user_octets_to_client{user="hello"} 230625379428 (214.79 GB)
telemt_user_unique_ips_current{user="hello"} 540
telemt_user_unique_ips_recent_window{user="hello"} 218
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 43804.7 (12h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2336517
telemt_connections_bad_total 147381
telemt_connections_current 4201
telemt_connections_me_current 4201
telemt_handshake_timeouts_total 52456
telemt_upstream_connect_attempt_total 8327
telemt_upstream_connect_success_total 8173
telemt_upstream_connect_fail_total 154
telemt_upstream_connect_attempts_per_request{bucket="1"} 8327
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4081
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4068
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 154
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 8309
telemt_me_reconnect_success_total 5961
telemt_me_reader_eof_total 6345
telemt_me_idle_close_by_peer_total 6345
telemt_me_seq_mismatch_total 13
telemt_me_route_drop_no_conn_total 1018359
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1927145
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 35
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8885
telemt_desync_full_logged_total 2945
telemt_desync_suppressed_total 5940
telemt_desync_frames_bucket_total{bucket="1_2"} 1632
telemt_desync_frames_bucket_total{bucket="3_10"} 3458
telemt_desync_frames_bucket_total{bucket="gt_10"} 3795
telemt_pool_swap_total 33
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 6141
telemt_me_refill_failed_total 73
telemt_me_writer_restored_same_endpoint_total 5939
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 180
telemt_user_connections_total{user="hello"} 1926876
telemt_user_connections_current{user="hello"} 4201
telemt_user_octets_from_client{user="hello"} 30717589848 (28.61 GB)
telemt_user_octets_to_client{user="hello"} 704870214916 (656.46 GB)
telemt_user_unique_ips_current{user="hello"} 1423
telemt_user_unique_ips_recent_window{user="hello"} 614
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 43801.8 (12h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1958699
telemt_connections_bad_total 235029
telemt_connections_current 3048
telemt_connections_me_current 3048
telemt_handshake_timeouts_total 46676
telemt_upstream_connect_attempt_total 7819
telemt_upstream_connect_success_total 7819
telemt_upstream_connect_attempts_per_request{bucket="1"} 7819
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4098
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3707
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_timeout_total 19
telemt_me_reconnect_attempts_total 5643
telemt_me_reconnect_success_total 5608
telemt_me_reader_eof_total 5935
telemt_me_idle_close_by_peer_total 5935
telemt_me_route_drop_no_conn_total 919657
telemt_me_route_drop_channel_closed_total 62
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1526364
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6836
telemt_desync_full_logged_total 2164
telemt_desync_suppressed_total 4672
telemt_desync_frames_bucket_total{bucket="1_2"} 1517
telemt_desync_frames_bucket_total{bucket="3_10"} 2511
telemt_desync_frames_bucket_total{bucket="gt_10"} 2808
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 5705
telemt_me_writer_restored_same_endpoint_total 5592
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 97
telemt_user_connections_total{user="hello"} 1524946
telemt_user_connections_current{user="hello"} 3048
telemt_user_octets_from_client{user="hello"} 23172393416 (21.58 GB)
telemt_user_octets_to_client{user="hello"} 698224721956 (650.27 GB)
telemt_user_unique_ips_current{user="hello"} 1073
telemt_user_unique_ips_recent_window{user="hello"} 506
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 43855.0 (12h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2018100
telemt_connections_bad_total 111590
telemt_connections_current 2987
telemt_connections_me_current 2987
telemt_relay_adaptive_promotions_total 1
telemt_relay_adaptive_hard_promotions_total 1
telemt_handshake_timeouts_total 52561
telemt_upstream_connect_attempt_total 16059
telemt_upstream_connect_success_total 15934
telemt_upstream_connect_fail_total 125
telemt_upstream_connect_attempts_per_request{bucket="1"} 16059
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11302
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4481
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 149
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 125
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 7988
telemt_me_reconnect_success_total 5562
telemt_me_reader_eof_total 5908
telemt_me_idle_close_by_peer_total 5907
telemt_me_route_drop_no_conn_total 1012914
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1516226
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5552
telemt_desync_full_logged_total 1884
telemt_desync_suppressed_total 3668
telemt_desync_frames_bucket_total{bucket="1_2"} 1150
telemt_desync_frames_bucket_total{bucket="3_10"} 2167
telemt_desync_frames_bucket_total{bucket="gt_10"} 2235
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 5841
telemt_me_refill_failed_total 70
telemt_me_writer_restored_same_endpoint_total 5538
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 272
telemt_me_writer_removed_unexpected_minus_restored_total 279
telemt_user_connections_total{user="hello"} 1522886
telemt_user_connections_current{user="hello"} 2987
telemt_user_octets_from_client{user="hello"} 17804872516 (16.58 GB)
telemt_user_octets_to_client{user="hello"} 442526953978 (412.14 GB)
telemt_user_msgs_from_client{user="hello"} 28643
telemt_user_msgs_to_client{user="hello"} 76631
telemt_user_unique_ips_current{user="hello"} 988
telemt_user_unique_ips_recent_window{user="hello"} 447
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 43798.5 (12h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2342902
telemt_connections_bad_total 550910
telemt_connections_current 3481
telemt_connections_me_current 3481
telemt_handshake_timeouts_total 49296
telemt_upstream_connect_attempt_total 7653
telemt_upstream_connect_success_total 7600
telemt_upstream_connect_fail_total 53
telemt_upstream_connect_attempts_per_request{bucket="1"} 7653
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3867
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3708
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 53
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 5442
telemt_me_reconnect_success_total 5397
telemt_me_reader_eof_total 5708
telemt_me_idle_close_by_peer_total 5708
telemt_me_route_drop_no_conn_total 682664
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1513345
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6985
telemt_desync_full_logged_total 2179
telemt_desync_suppressed_total 4806
telemt_desync_frames_bucket_total{bucket="1_2"} 1402
telemt_desync_frames_bucket_total{bucket="3_10"} 3050
telemt_desync_frames_bucket_total{bucket="gt_10"} 2533
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 5476
telemt_me_writer_restored_same_endpoint_total 5373
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 79
telemt_user_connections_total{user="hello"} 1512497
telemt_user_connections_current{user="hello"} 3481
telemt_user_octets_from_client{user="hello"} 28206892808 (26.27 GB)
telemt_user_octets_to_client{user="hello"} 662594686784 (617.09 GB)
telemt_user_unique_ips_current{user="hello"} 1194
telemt_user_unique_ips_recent_window{user="hello"} 562
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 43810.4 (12h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 420239
telemt_connections_bad_total 18091
telemt_connections_current 952
telemt_connections_me_current 952
telemt_handshake_timeouts_total 3364
telemt_upstream_connect_attempt_total 11077
telemt_upstream_connect_success_total 10797
telemt_upstream_connect_fail_total 280
telemt_upstream_connect_attempts_per_request{bucket="1"} 11077
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5386
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5410
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 280
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 13981
telemt_me_reconnect_success_total 8593
telemt_me_reader_eof_total 9115
telemt_me_idle_close_by_peer_total 9115
telemt_me_route_drop_no_conn_total 212486
telemt_me_route_drop_channel_closed_total 22
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 377803
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 655
telemt_desync_full_logged_total 223
telemt_desync_suppressed_total 432
telemt_desync_frames_bucket_total{bucket="1_2"} 168
telemt_desync_frames_bucket_total{bucket="3_10"} 258
telemt_desync_frames_bucket_total{bucket="gt_10"} 229
telemt_pool_swap_total 21
telemt_pool_stale_pick_total 194
telemt_me_writer_removed_unexpected_total 8833
telemt_me_refill_failed_total 167
telemt_me_writer_restored_same_endpoint_total 8563
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 240
telemt_user_connections_total{user="hello"} 377774
telemt_user_connections_current{user="hello"} 952
telemt_user_octets_from_client{user="hello"} 6041654892 (5.63 GB)
telemt_user_octets_to_client{user="hello"} 148080322788 (137.91 GB)
telemt_user_unique_ips_current{user="hello"} 352
telemt_user_unique_ips_recent_window{user="hello"} 142
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 43800.7 (12h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1590646
telemt_connections_bad_total 133239
telemt_connections_current 3138
telemt_connections_me_current 3138
telemt_handshake_timeouts_total 67181
telemt_upstream_connect_attempt_total 8858
telemt_upstream_connect_success_total 8857
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 8858
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4758
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4096
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 50
telemt_me_reconnect_attempts_total 7997
telemt_me_reconnect_success_total 6645
telemt_me_reader_eof_total 7044
telemt_me_idle_close_by_peer_total 7043
telemt_me_route_drop_no_conn_total 622663
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1328379
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7493
telemt_desync_full_logged_total 2454
telemt_desync_suppressed_total 5039
telemt_desync_frames_bucket_total{bucket="1_2"} 1417
telemt_desync_frames_bucket_total{bucket="3_10"} 2817
telemt_desync_frames_bucket_total{bucket="gt_10"} 3259
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 6768
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 6630
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 123
telemt_user_connections_total{user="hello"} 1327227
telemt_user_connections_current{user="hello"} 3138
telemt_user_octets_from_client{user="hello"} 18136424260 (16.89 GB)
telemt_user_octets_to_client{user="hello"} 644781014580 (600.50 GB)
telemt_user_unique_ips_current{user="hello"} 1002
telemt_user_unique_ips_recent_window{user="hello"} 451
```