# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### **Принимаю донаты криптой для добавления и продления серверов:**
- TON (Можно отправлять TON и USDT в сети TON):
```
UQAyIvWts4-gC0b5ouoy_JNDfBEe337c7oOBqpGXFB8fJUzB
```
### **Спасибо:**
- Ivan Morozov - 20$

_Можете писать свой ник в коментарии к переводу_

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-60
- Краткое описание тарифа: 4 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 26 апреля
- Ссылка:
```bash
tg://proxy?server=s1.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## psb.hosting (2 сервера)
- Локация: Finland
- Тариф: FI-200
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 12$
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

## rdp-onedash.ru (2 сервера)
- Локация: Нидерланды
- Тариф: Mini
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 844 RUB
- Ссылка:
```bash
tg://proxy?server=s5.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## hostvds.com
- Локация: Франция, Париж
- Тариф: Highload-2
- Краткое описание тарифа: 2 vCore, 8 Gb ram, 10 Gbit/s
- Цена в месяц: €12.57
- Ссылка:
```bash
tg://proxy?server=s6.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## 4vps.su (2 сервера)
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

# Server Metrics 2026-03-22 03:27:05 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 22828.8 (6h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 343871
telemt_connections_bad_total 22820
telemt_connections_current 992
telemt_connections_me_current 992
telemt_handshake_timeouts_total 19556
telemt_upstream_connect_attempt_total 9599
telemt_upstream_connect_success_total 9597
telemt_upstream_connect_attempts_per_request{bucket="1"} 9597
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3424
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6153
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 274
telemt_me_reconnect_success_total 148
telemt_me_reader_eof_total 144
telemt_me_idle_close_by_peer_total 144
telemt_me_route_drop_no_conn_total 64664
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 283507
telemt_me_endpoint_quarantine_total 186
telemt_me_single_endpoint_shadow_rotate_total 195
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 45
telemt_desync_total 2548
telemt_desync_full_logged_total 700
telemt_desync_suppressed_total 1848
telemt_desync_frames_bucket_total{bucket="1_2"} 869
telemt_desync_frames_bucket_total{bucket="3_10"} 960
telemt_desync_frames_bucket_total{bucket="gt_10"} 719
telemt_pool_swap_total 25
telemt_pool_force_close_total 654
telemt_me_writer_close_signal_drop_total 46
telemt_me_draining_writers_reap_progress_total 8670
telemt_me_writer_removed_unexpected_total 143
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 584
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 8220
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 649
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 8016
telemt_me_writer_teardown_success_total{mode="normal"} 8804
telemt_me_writer_teardown_noop_total 8671
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 16993
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 17284
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 17381
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 17441
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 17473
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 17475
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 17475
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 17475
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 17475
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 17475
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 17475
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 17475
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 17475
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.012610
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 17475
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 46
telemt_me_refill_failed_total 7
telemt_me_writer_restored_same_endpoint_total 134
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 282989
telemt_user_connections_current{user="hello"} 992
telemt_user_octets_from_client{user="hello"} 3411473852 (3.18 GB)
telemt_user_octets_to_client{user="hello"} 100110636924 (93.24 GB)
telemt_user_unique_ips_current{user="hello"} 404
telemt_user_unique_ips_recent_window{user="hello"} 141
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 36195.1 (10h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 824025
telemt_connections_bad_total 52892
telemt_connections_current 933
telemt_connections_me_current 933
telemt_handshake_timeouts_total 30210
telemt_upstream_connect_attempt_total 16950
telemt_upstream_connect_success_total 16687
telemt_upstream_connect_fail_total 240
telemt_upstream_connect_attempts_per_request{bucket="1"} 16927
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7323
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9318
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 240
telemt_me_reconnect_attempts_total 1391
telemt_me_reconnect_success_total 525
telemt_me_reader_eof_total 465
telemt_me_idle_close_by_peer_total 465
telemt_me_route_drop_no_conn_total 346565
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 651704
telemt_me_endpoint_quarantine_total 344
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 19
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 19
telemt_me_single_endpoint_shadow_rotate_total 293
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 45
telemt_desync_total 2799
telemt_desync_full_logged_total 1607
telemt_desync_suppressed_total 1192
telemt_desync_frames_bucket_total{bucket="1_2"} 592
telemt_desync_frames_bucket_total{bucket="3_10"} 1066
telemt_desync_frames_bucket_total{bucket="gt_10"} 1141
telemt_pool_swap_total 39
telemt_pool_force_close_total 1028
telemt_me_writer_close_signal_drop_total 72
telemt_me_draining_writers_reap_progress_total 14998
telemt_me_writer_removed_unexpected_total 442
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1258
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14192
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1006
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 22
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13970
telemt_me_writer_teardown_success_total{mode="normal"} 15450
telemt_me_writer_teardown_noop_total 14998
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 29916
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 30226
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 30342
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 30434
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 30446
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 30448
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 30448
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 30448
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 30448
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 30448
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 30448
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 30448
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 30448
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.783248
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 30448
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 72
telemt_me_refill_failed_total 45
telemt_me_writer_restored_same_endpoint_total 392
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 38
telemt_user_connections_total{user="hello"} 650773
telemt_user_connections_current{user="hello"} 933
telemt_user_octets_from_client{user="hello"} 10597748560 (9.87 GB)
telemt_user_octets_to_client{user="hello"} 231710297112 (215.80 GB)
telemt_user_unique_ips_current{user="hello"} 607
telemt_user_unique_ips_recent_window{user="hello"} 131
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 111055.0 (30h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7838794
telemt_connections_bad_total 645568
telemt_connections_current 1472
telemt_connections_me_current 1472
telemt_handshake_timeouts_total 257554
telemt_upstream_connect_attempt_total 41370
telemt_upstream_connect_success_total 41295
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 41302
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18669
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22448
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 172
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1599
telemt_me_reconnect_success_total 836
telemt_me_reader_eof_total 845
telemt_me_idle_close_by_peer_total 845
telemt_me_route_drop_no_conn_total 4550524
telemt_me_route_drop_channel_closed_total 66
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6335883
telemt_me_endpoint_quarantine_total 717
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 830
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 25
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_desync_total 26665
telemt_desync_full_logged_total 8837
telemt_desync_suppressed_total 17828
telemt_desync_frames_bucket_total{bucket="1_2"} 5758
telemt_desync_frames_bucket_total{bucket="3_10"} 10414
telemt_desync_frames_bucket_total{bucket="gt_10"} 10493
telemt_pool_swap_total 120
telemt_pool_force_close_total 3962
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 608
telemt_me_draining_writers_reap_progress_total 37749
telemt_me_writer_removed_unexpected_total 813
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3158
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 34939
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3722
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 240
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 33787
telemt_me_writer_teardown_success_total{mode="normal"} 38097
telemt_me_writer_teardown_noop_total 37793
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 69554
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 71424
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 72436
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 73976
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 75034
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 75589
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 75879
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 75890
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 75890
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 75890
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 75890
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 75890
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 75890
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 161.797100
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 75890
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 608
telemt_me_refill_failed_total 40
telemt_me_writer_restored_same_endpoint_total 745
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 63
telemt_user_connections_total{user="hello"} 6327913
telemt_user_connections_current{user="hello"} 1472
telemt_user_octets_from_client{user="hello"} 107566447172 (100.18 GB)
telemt_user_octets_to_client{user="hello"} 2116238703324 (1.92 TB)
telemt_user_unique_ips_current{user="hello"} 778
telemt_user_unique_ips_recent_window{user="hello"} 199
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 111056.6 (30h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6485231
telemt_connections_bad_total 590608
telemt_connections_current 1616
telemt_connections_me_current 1616
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 214749
telemt_upstream_connect_attempt_total 45363
telemt_upstream_connect_success_total 44971
telemt_upstream_connect_fail_total 195
telemt_upstream_connect_attempts_per_request{bucket="1"} 45166
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22300
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22081
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 557
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 195
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 1955
telemt_me_reconnect_success_total 886
telemt_me_reader_eof_total 858
telemt_me_idle_close_by_peer_total 858
telemt_me_route_drop_no_conn_total 2270292
telemt_me_route_drop_channel_closed_total 270
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4834927
telemt_me_endpoint_quarantine_total 698
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 857
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 29
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_desync_total 22792
telemt_desync_full_logged_total 7770
telemt_desync_suppressed_total 15022
telemt_desync_frames_bucket_total{bucket="1_2"} 5480
telemt_desync_frames_bucket_total{bucket="3_10"} 8859
telemt_desync_frames_bucket_total{bucket="gt_10"} 8453
telemt_pool_swap_total 121
telemt_pool_force_close_total 3594
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 368
telemt_me_draining_writers_reap_progress_total 36259
telemt_me_writer_removed_unexpected_total 842
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3010
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 34029
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3381
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 213
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 32665
telemt_me_writer_teardown_success_total{mode="normal"} 37039
telemt_me_writer_teardown_noop_total 36265
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 69971
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 71535
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 72108
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 72688
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 73099
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 73284
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 73304
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 73304
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 73304
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 73304
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 73304
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 73304
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 73304
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 48.461009
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 73304
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 368
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 775
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 59
telemt_user_connections_total{user="hello"} 4757006
telemt_user_connections_current{user="hello"} 1616
telemt_user_octets_from_client{user="hello"} 141224104501 (131.53 GB)
telemt_user_octets_to_client{user="hello"} 2252342238183 (2.05 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 790
telemt_user_unique_ips_recent_window{user="hello"} 167
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 111021.5 (30h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6353636
telemt_connections_bad_total 549893
telemt_connections_current 1552
telemt_connections_me_current 1552
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 206512
telemt_upstream_connect_attempt_total 51479
telemt_upstream_connect_success_total 51098
telemt_upstream_connect_fail_total 136
telemt_upstream_connect_attempts_per_request{bucket="1"} 51234
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25973
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23520
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 522
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1083
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 136
telemt_me_keepalive_timeout_total 58
telemt_me_reconnect_attempts_total 2087
telemt_me_reconnect_success_total 927
telemt_me_reader_eof_total 875
telemt_me_idle_close_by_peer_total 875
telemt_me_route_drop_no_conn_total 2164096
telemt_me_route_drop_channel_closed_total 125
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4721012
telemt_me_endpoint_quarantine_total 784
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 830
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 41
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_desync_total 22717
telemt_desync_full_logged_total 7655
telemt_desync_suppressed_total 15062
telemt_desync_frames_bucket_total{bucket="1_2"} 5546
telemt_desync_frames_bucket_total{bucket="3_10"} 8706
telemt_desync_frames_bucket_total{bucket="gt_10"} 8465
telemt_pool_swap_total 120
telemt_pool_force_close_total 3482
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 391
telemt_me_draining_writers_reap_progress_total 37353
telemt_me_writer_removed_unexpected_total 844
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3093
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 35121
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3267
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 215
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 33871
telemt_me_writer_teardown_success_total{mode="normal"} 38214
telemt_me_writer_teardown_noop_total 37365
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 72907
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 74341
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 74812
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 75313
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 75532
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 75559
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 75579
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 75579
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 75579
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 75579
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 75579
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 75579
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 75579
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 27.848042
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 75579
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 391
telemt_me_refill_failed_total 64
telemt_me_writer_restored_same_endpoint_total 805
telemt_me_writer_restored_fallback_total 5
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 34
telemt_user_connections_total{user="hello"} 4716478
telemt_user_connections_current{user="hello"} 1552
telemt_user_octets_from_client{user="hello"} 134652528435 (125.40 GB)
telemt_user_octets_to_client{user="hello"} 2164863583663 (1.97 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 760
telemt_user_unique_ips_recent_window{user="hello"} 188
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 111074.8 (30h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20554501
telemt_connections_bad_total 1665431
telemt_connections_current 2324
telemt_connections_me_current 2324
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 617215
telemt_upstream_connect_attempt_total 200317
telemt_upstream_connect_success_total 182191
telemt_upstream_connect_fail_total 16347
telemt_upstream_connect_attempts_per_request{bucket="1"} 198538
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 128682
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 43355
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1221
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8933
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16347
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 65036
telemt_me_reconnect_success_total 2349
telemt_me_reader_eof_total 1479
telemt_me_idle_close_by_peer_total 1478
telemt_me_route_drop_no_conn_total 39531821
telemt_me_route_drop_channel_closed_total 126
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16582647
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 868
telemt_me_single_endpoint_outage_enter_total 135
telemt_me_single_endpoint_outage_exit_total 135
telemt_me_single_endpoint_outage_reconnect_attempt_total 285
telemt_me_single_endpoint_outage_reconnect_success_total 70
telemt_me_single_endpoint_quarantine_bypass_total 285
telemt_me_single_endpoint_shadow_rotate_total 870
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 65
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 45
telemt_desync_total 32163
telemt_desync_full_logged_total 9671
telemt_desync_suppressed_total 22492
telemt_desync_frames_bucket_total{bucket="1_2"} 6974
telemt_desync_frames_bucket_total{bucket="3_10"} 14269
telemt_desync_frames_bucket_total{bucket="gt_10"} 10920
telemt_pool_swap_total 115
telemt_pool_force_close_total 3714
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 815
telemt_me_draining_writers_reap_progress_total 34880
telemt_me_writer_removed_unexpected_total 2177
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4690
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 32108
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 24
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3189
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 525
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 31166
telemt_me_writer_teardown_success_total{mode="normal"} 36798
telemt_me_writer_teardown_noop_total 34907
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 64803
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 67329
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 68636
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 70310
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 71261
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 71603
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 71686
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 71688
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 71691
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 71696
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 71696
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 71700
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 71705
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 215.816427
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 71705
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 815
telemt_me_refill_failed_total 3808
telemt_me_writer_restored_same_endpoint_total 1610
telemt_me_writer_restored_fallback_total 21
telemt_me_no_writer_failfast_total 666
telemt_me_async_recovery_trigger_total 14678
telemt_me_writer_removed_unexpected_minus_restored_total 546
telemt_user_connections_total{user="hello"} 16715723
telemt_user_connections_current{user="hello"} 2324
telemt_user_octets_from_client{user="hello"} 227385156352 (211.77 GB)
telemt_user_octets_to_client{user="hello"} 1230337793893 (1.12 TB)
telemt_user_msgs_from_client{user="hello"} 395497
telemt_user_msgs_to_client{user="hello"} 785476
telemt_user_unique_ips_current{user="hello"} 1113
telemt_user_unique_ips_recent_window{user="hello"} 264
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 111027.3 (30h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6107868
telemt_connections_bad_total 583224
telemt_connections_current 1388
telemt_connections_me_current 1388
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 128734
telemt_upstream_connect_attempt_total 60180
telemt_upstream_connect_success_total 59486
telemt_upstream_connect_fail_total 593
telemt_upstream_connect_attempts_per_request{bucket="1"} 60079
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34611
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24520
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 354
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 593
telemt_me_reconnect_attempts_total 69750
telemt_me_reconnect_success_total 1814
telemt_me_reader_eof_total 1597
telemt_me_idle_close_by_peer_total 1596
telemt_me_route_drop_no_conn_total 2400228
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4751411
telemt_me_endpoint_quarantine_total 755
telemt_me_single_endpoint_outage_enter_total 23
telemt_me_single_endpoint_outage_exit_total 23
telemt_me_single_endpoint_outage_reconnect_attempt_total 24
telemt_me_single_endpoint_outage_reconnect_success_total 23
telemt_me_single_endpoint_quarantine_bypass_total 24
telemt_me_single_endpoint_shadow_rotate_total 844
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 34
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_desync_total 23642
telemt_desync_full_logged_total 8322
telemt_desync_suppressed_total 15320
telemt_desync_frames_bucket_total{bucket="1_2"} 4540
telemt_desync_frames_bucket_total{bucket="3_10"} 9156
telemt_desync_frames_bucket_total{bucket="gt_10"} 9946
telemt_pool_swap_total 115
telemt_pool_force_close_total 3293
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 397
telemt_me_draining_writers_reap_progress_total 39253
telemt_me_writer_removed_unexpected_total 1634
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4011
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 36908
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2892
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 401
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 35960
telemt_me_writer_teardown_success_total{mode="normal"} 40919
telemt_me_writer_teardown_noop_total 39254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 78906
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 79738
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 80021
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 80141
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 80170
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 80173
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 80173
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 80173
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 80173
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 80173
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 80173
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 80173
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 80173
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.174607
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 80173
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 397
telemt_me_refill_failed_total 4210
telemt_me_writer_restored_same_endpoint_total 1522
telemt_me_writer_restored_fallback_total 35
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7305
telemt_me_writer_removed_unexpected_minus_restored_total 77
telemt_user_connections_total{user="hello"} 4744117
telemt_user_connections_current{user="hello"} 1388
telemt_user_octets_from_client{user="hello"} 125476962308 (116.86 GB)
telemt_user_octets_to_client{user="hello"} 1935850720186 (1.76 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 671
telemt_user_unique_ips_recent_window{user="hello"} 210
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 47863.2 (13h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4031781
telemt_connections_bad_total 163516
telemt_connections_current 1785
telemt_connections_me_current 1785
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 1630105
telemt_upstream_connect_attempt_total 28903
telemt_upstream_connect_success_total 28717
telemt_upstream_connect_fail_total 179
telemt_upstream_connect_attempts_per_request{bucket="1"} 28896
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17888
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10752
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 77
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 179
telemt_me_reconnect_attempts_total 45877
telemt_me_reconnect_success_total 985
telemt_me_reader_eof_total 669
telemt_me_idle_close_by_peer_total 669
telemt_me_route_drop_no_conn_total 1031853
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1972952
telemt_me_endpoint_quarantine_total 360
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 50
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 50
telemt_me_single_endpoint_shadow_rotate_total 369
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 10615
telemt_desync_full_logged_total 3673
telemt_desync_suppressed_total 6942
telemt_desync_frames_bucket_total{bucket="1_2"} 1918
telemt_desync_frames_bucket_total{bucket="3_10"} 4073
telemt_desync_frames_bucket_total{bucket="gt_10"} 4624
telemt_pool_swap_total 52
telemt_pool_force_close_total 1526
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 139
telemt_me_draining_writers_reap_progress_total 17806
telemt_me_writer_removed_unexpected_total 742
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1582
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16993
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1320
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 206
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16280
telemt_me_writer_teardown_success_total{mode="normal"} 18575
telemt_me_writer_teardown_noop_total 17808
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 35853
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 36138
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 36277
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 36383
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 36383
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 36383
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 36383
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 36383
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 36383
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 36383
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 36383
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 36383
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 36383
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.495350
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 36383
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 139
telemt_me_refill_failed_total 2608
telemt_me_writer_restored_same_endpoint_total 881
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4264
telemt_user_connections_total{user="hello"} 1976495
telemt_user_connections_current{user="hello"} 1785
telemt_user_octets_from_client{user="hello"} 54948106864 (51.17 GB)
telemt_user_octets_to_client{user="hello"} 838494202238 (780.91 GB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 905
telemt_user_unique_ips_recent_window{user="hello"} 154
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 28834.0 (8h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 208639
telemt_connections_bad_total 1761
telemt_connections_current 374
telemt_connections_me_current 374
telemt_handshake_timeouts_total 5685
telemt_upstream_connect_attempt_total 13856
telemt_upstream_connect_success_total 13824
telemt_upstream_connect_fail_total 30
telemt_upstream_connect_attempts_per_request{bucket="1"} 13854
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5834
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7911
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 79
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 30
telemt_me_reconnect_attempts_total 298
telemt_me_reconnect_success_total 175
telemt_me_reader_eof_total 180
telemt_me_idle_close_by_peer_total 180
telemt_me_route_drop_no_conn_total 58016
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 184267
telemt_me_endpoint_quarantine_total 283
telemt_me_single_endpoint_shadow_rotate_total 248
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_me_writers_warm_current 7
telemt_desync_total 1062
telemt_desync_full_logged_total 273
telemt_desync_suppressed_total 789
telemt_desync_frames_bucket_total{bucket="1_2"} 396
telemt_desync_frames_bucket_total{bucket="3_10"} 399
telemt_desync_frames_bucket_total{bucket="gt_10"} 267
telemt_pool_swap_total 31
telemt_pool_force_close_total 692
telemt_me_writer_close_signal_drop_total 24
telemt_me_draining_writers_reap_progress_total 12528
telemt_me_writer_removed_unexpected_total 173
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 801
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 11907
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 690
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 11836
telemt_me_writer_teardown_success_total{mode="normal"} 12708
telemt_me_writer_teardown_noop_total 12528
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 25024
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 25208
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 25226
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 25236
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 25236
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 25236
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 25236
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 25236
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 25236
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 25236
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 25236
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 25236
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 25236
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.050420
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 25236
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 24
telemt_me_refill_failed_total 7
telemt_me_writer_restored_same_endpoint_total 159
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 13
telemt_user_connections_total{user="hello"} 183945
telemt_user_connections_current{user="hello"} 374
telemt_user_octets_from_client{user="hello"} 3255120468 (3.03 GB)
telemt_user_octets_to_client{user="hello"} 114614760400 (106.74 GB)
telemt_user_unique_ips_current{user="hello"} 165
telemt_user_unique_ips_recent_window{user="hello"} 51
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 111031.6 (30h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7425193
telemt_connections_bad_total 747624
telemt_connections_current 1892
telemt_connections_me_current 1892
telemt_handshake_timeouts_total 211395
telemt_upstream_connect_attempt_total 43635
telemt_upstream_connect_success_total 43476
telemt_upstream_connect_fail_total 122
telemt_upstream_connect_attempts_per_request{bucket="1"} 43598
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21533
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21902
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 122
telemt_me_reconnect_attempts_total 1594
telemt_me_reconnect_success_total 858
telemt_me_reader_eof_total 843
telemt_me_idle_close_by_peer_total 843
telemt_me_route_drop_no_conn_total 2139187
telemt_me_route_drop_channel_closed_total 52
telemt_me_route_drop_queue_full_total 23
telemt_me_route_drop_queue_full_profile_total{profile="high"} 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5540105
telemt_me_endpoint_quarantine_total 785
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 857
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 31
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 21755
telemt_desync_full_logged_total 7126
telemt_desync_suppressed_total 14629
telemt_desync_frames_bucket_total{bucket="1_2"} 5467
telemt_desync_frames_bucket_total{bucket="3_10"} 7876
telemt_desync_frames_bucket_total{bucket="gt_10"} 8412
telemt_pool_swap_total 123
telemt_pool_force_close_total 3287
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 393
telemt_me_draining_writers_reap_progress_total 39385
telemt_me_writer_removed_unexpected_total 812
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3080
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 37138
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3199
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 36098
telemt_me_writer_teardown_success_total{mode="normal"} 40218
telemt_me_writer_teardown_noop_total 39387
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 78238
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 79139
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 79317
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 79517
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 79605
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 79605
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 79605
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 79605
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 79605
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 79605
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 79605
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 79605
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 79605
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.687243
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 79605
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 393
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 767
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 37
telemt_user_connections_total{user="hello"} 5515052
telemt_user_connections_current{user="hello"} 1892
telemt_user_octets_from_client{user="hello"} 110365416236 (102.79 GB)
telemt_user_octets_to_client{user="hello"} 2569639829564 (2.34 TB)
telemt_user_unique_ips_current{user="hello"} 831
telemt_user_unique_ips_recent_window{user="hello"} 192
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 111028.3 (30h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6426335
telemt_connections_bad_total 633603
telemt_connections_current 1793
telemt_connections_me_current 1793
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 174472
telemt_upstream_connect_attempt_total 59469
telemt_upstream_connect_success_total 59021
telemt_upstream_connect_fail_total 389
telemt_upstream_connect_attempts_per_request{bucket="1"} 59410
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34308
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23579
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 616
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 389
telemt_me_reconnect_attempts_total 5601
telemt_me_reconnect_success_total 1201
telemt_me_reader_eof_total 1084
telemt_me_idle_close_by_peer_total 1084
telemt_me_seq_mismatch_total 51
telemt_me_route_drop_no_conn_total 2192368
telemt_me_route_drop_channel_closed_total 189
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4905820
telemt_me_endpoint_quarantine_total 880
telemt_me_single_endpoint_outage_enter_total 28
telemt_me_single_endpoint_outage_exit_total 28
telemt_me_single_endpoint_outage_reconnect_attempt_total 28
telemt_me_single_endpoint_outage_reconnect_success_total 26
telemt_me_single_endpoint_quarantine_bypass_total 28
telemt_me_single_endpoint_shadow_rotate_total 850
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 33
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 45
telemt_desync_total 20359
telemt_desync_full_logged_total 6787
telemt_desync_suppressed_total 13572
telemt_desync_frames_bucket_total{bucket="1_2"} 5212
telemt_desync_frames_bucket_total{bucket="3_10"} 7425
telemt_desync_frames_bucket_total{bucket="gt_10"} 7722
telemt_pool_swap_total 121
telemt_pool_force_close_total 3242
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 386
telemt_me_draining_writers_reap_progress_total 37958
telemt_me_writer_removed_unexpected_total 1096
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3620
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 35488
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3019
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 223
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 34716
telemt_me_writer_teardown_success_total{mode="normal"} 39108
telemt_me_writer_teardown_noop_total 37962
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 75416
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 76482
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 76837
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 77032
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 77070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 77070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 77070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 77070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 77070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 77070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 77070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 77070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 77070
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 11.132763
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 77070
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 386
telemt_me_refill_failed_total 254
telemt_me_writer_restored_same_endpoint_total 937
telemt_me_writer_restored_fallback_total 69
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 76
telemt_me_writer_removed_unexpected_minus_restored_total 90
telemt_user_connections_total{user="hello"} 4908755
telemt_user_connections_current{user="hello"} 1793
telemt_user_octets_from_client{user="hello"} 92710769997 (86.34 GB)
telemt_user_octets_to_client{user="hello"} 2098641498080 (1.91 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 747
telemt_user_unique_ips_recent_window{user="hello"} 190
```