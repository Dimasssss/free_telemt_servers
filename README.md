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

# Server Metrics 2026-03-22 04:28:13 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 26510.6 (7h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 425184
telemt_connections_bad_total 27690
telemt_connections_current 1032
telemt_connections_me_current 1032
telemt_handshake_timeouts_total 23817
telemt_upstream_connect_attempt_total 11098
telemt_upstream_connect_success_total 11097
telemt_upstream_connect_attempts_per_request{bucket="1"} 11097
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3934
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7143
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 302
telemt_me_reconnect_success_total 173
telemt_me_reader_eof_total 169
telemt_me_idle_close_by_peer_total 169
telemt_me_route_drop_no_conn_total 87316
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 351185
telemt_me_endpoint_quarantine_total 209
telemt_me_single_endpoint_shadow_rotate_total 224
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 4
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
telemt_desync_total 3175
telemt_desync_full_logged_total 866
telemt_desync_suppressed_total 2309
telemt_desync_frames_bucket_total{bucket="1_2"} 1094
telemt_desync_frames_bucket_total{bucket="3_10"} 1205
telemt_desync_frames_bucket_total{bucket="gt_10"} 876
telemt_pool_swap_total 29
telemt_pool_force_close_total 765
telemt_me_writer_close_signal_drop_total 58
telemt_me_draining_writers_reap_progress_total 10019
telemt_me_writer_removed_unexpected_total 167
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 677
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 9501
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 760
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 9254
telemt_me_writer_teardown_success_total{mode="normal"} 10178
telemt_me_writer_teardown_noop_total 10020
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 19581
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 19918
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 20057
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 20149
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 20192
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 20198
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 20198
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 20198
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 20198
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 20198
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 20198
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 20198
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 20198
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.650948
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 20198
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 58
telemt_me_refill_failed_total 7
telemt_me_writer_restored_same_endpoint_total 156
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 350263
telemt_user_connections_current{user="hello"} 1032
telemt_user_octets_from_client{user="hello"} 4342225700 (4.04 GB)
telemt_user_octets_to_client{user="hello"} 122192980852 (113.80 GB)
telemt_user_unique_ips_current{user="hello"} 442
telemt_user_unique_ips_recent_window{user="hello"} 139
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 39876.8 (11h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 879690
telemt_connections_bad_total 59025
telemt_connections_current 562
telemt_connections_me_current 562
telemt_handshake_timeouts_total 31343
telemt_upstream_connect_attempt_total 18703
telemt_upstream_connect_success_total 18410
telemt_upstream_connect_fail_total 262
telemt_upstream_connect_attempts_per_request{bucket="1"} 18672
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8115
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10249
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 262
telemt_me_reconnect_attempts_total 1527
telemt_me_reconnect_success_total 573
telemt_me_reader_eof_total 510
telemt_me_idle_close_by_peer_total 510
telemt_me_route_drop_no_conn_total 357468
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 697239
telemt_me_endpoint_quarantine_total 372
telemt_me_single_endpoint_outage_enter_total 20
telemt_me_single_endpoint_outage_exit_total 20
telemt_me_single_endpoint_outage_reconnect_attempt_total 20
telemt_me_single_endpoint_outage_reconnect_success_total 20
telemt_me_single_endpoint_quarantine_bypass_total 20
telemt_me_single_endpoint_shadow_rotate_total 325
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 23
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
telemt_desync_total 2968
telemt_desync_full_logged_total 1701
telemt_desync_suppressed_total 1267
telemt_desync_frames_bucket_total{bucket="1_2"} 629
telemt_desync_frames_bucket_total{bucket="3_10"} 1141
telemt_desync_frames_bucket_total{bucket="gt_10"} 1198
telemt_pool_swap_total 43
telemt_pool_force_close_total 1149
telemt_me_writer_close_signal_drop_total 82
telemt_me_draining_writers_reap_progress_total 16581
telemt_me_writer_removed_unexpected_total 486
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1387
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15691
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1127
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 22
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15432
telemt_me_writer_teardown_success_total{mode="normal"} 17078
telemt_me_writer_teardown_noop_total 16581
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 33086
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 33422
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 33546
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 33645
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 33657
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 33659
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 33659
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 33659
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 33659
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 33659
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 33659
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 33659
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 33659
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.062358
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 33659
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 82
telemt_me_refill_failed_total 50
telemt_me_writer_restored_same_endpoint_total 430
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 44
telemt_user_connections_total{user="hello"} 696142
telemt_user_connections_current{user="hello"} 562
telemt_user_octets_from_client{user="hello"} 11195301732 (10.43 GB)
telemt_user_octets_to_client{user="hello"} 252050353304 (234.74 GB)
telemt_user_unique_ips_current{user="hello"} 393
telemt_user_unique_ips_recent_window{user="hello"} 188
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 114736.6 (31h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8017275
telemt_connections_bad_total 681360
telemt_connections_current 2262
telemt_connections_me_current 2262
telemt_handshake_timeouts_total 263134
telemt_upstream_connect_attempt_total 42851
telemt_upstream_connect_success_total 42773
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 42781
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19361
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23229
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 177
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1634
telemt_me_reconnect_success_total 850
telemt_me_reader_eof_total 859
telemt_me_idle_close_by_peer_total 859
telemt_me_route_drop_no_conn_total 4582516
telemt_me_route_drop_channel_closed_total 66
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6459349
telemt_me_endpoint_quarantine_total 742
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 860
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 27
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
telemt_desync_total 27075
telemt_desync_full_logged_total 8998
telemt_desync_suppressed_total 18077
telemt_desync_frames_bucket_total{bucket="1_2"} 5858
telemt_desync_frames_bucket_total{bucket="3_10"} 10581
telemt_desync_frames_bucket_total{bucket="gt_10"} 10636
telemt_pool_swap_total 124
telemt_pool_force_close_total 4074
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 618
telemt_me_draining_writers_reap_progress_total 39106
telemt_me_writer_removed_unexpected_total 827
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3245
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 36223
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3834
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 240
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 35032
telemt_me_writer_teardown_success_total{mode="normal"} 39468
telemt_me_writer_teardown_noop_total 39150
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 72182
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 74085
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 75111
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 76667
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 77740
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 78317
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 78607
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 78618
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 78618
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 78618
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 78618
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 78618
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 78618
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 164.464771
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 78618
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 618
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 758
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 64
telemt_user_connections_total{user="hello"} 6451073
telemt_user_connections_current{user="hello"} 2262
telemt_user_octets_from_client{user="hello"} 109674256728 (102.14 GB)
telemt_user_octets_to_client{user="hello"} 2169973559836 (1.97 TB)
telemt_user_unique_ips_current{user="hello"} 1053
telemt_user_unique_ips_recent_window{user="hello"} 308
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 114738.1 (31h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6618657
telemt_connections_bad_total 595100
telemt_connections_current 2261
telemt_connections_me_current 2261
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 219541
telemt_upstream_connect_attempt_total 46782
telemt_upstream_connect_success_total 46385
telemt_upstream_connect_fail_total 200
telemt_upstream_connect_attempts_per_request{bucket="1"} 46585
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22964
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22831
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 557
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 200
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 1976
telemt_me_reconnect_success_total 907
telemt_me_reader_eof_total 881
telemt_me_idle_close_by_peer_total 881
telemt_me_route_drop_no_conn_total 2294732
telemt_me_route_drop_channel_closed_total 282
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4940881
telemt_me_endpoint_quarantine_total 726
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 886
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 30
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
telemt_desync_total 23072
telemt_desync_full_logged_total 7884
telemt_desync_suppressed_total 15188
telemt_desync_frames_bucket_total{bucket="1_2"} 5541
telemt_desync_frames_bucket_total{bucket="3_10"} 8960
telemt_desync_frames_bucket_total{bucket="gt_10"} 8571
telemt_pool_swap_total 125
telemt_pool_force_close_total 3706
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 374
telemt_me_draining_writers_reap_progress_total 37548
telemt_me_writer_removed_unexpected_total 863
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3100
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 35251
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3489
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 217
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 33842
telemt_me_writer_teardown_success_total{mode="normal"} 38351
telemt_me_writer_teardown_noop_total 37554
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 72530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 74115
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 74701
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 75287
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 75700
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 75885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 75905
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 75905
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 75905
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 75905
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 75905
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 75905
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 75905
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 48.816452
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 75905
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 374
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 792
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 61
telemt_user_connections_total{user="hello"} 4862538
telemt_user_connections_current{user="hello"} 2261
telemt_user_octets_from_client{user="hello"} 143475467445 (133.62 GB)
telemt_user_octets_to_client{user="hello"} 2317763764247 (2.11 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1008
telemt_user_unique_ips_recent_window{user="hello"} 247
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 114702.3 (31h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6479583
telemt_connections_bad_total 553411
telemt_connections_current 1949
telemt_connections_me_current 1949
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 214137
telemt_upstream_connect_attempt_total 53236
telemt_upstream_connect_success_total 52741
telemt_upstream_connect_fail_total 142
telemt_upstream_connect_attempts_per_request{bucket="1"} 52883
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26516
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24423
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 652
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 142
telemt_me_keepalive_timeout_total 62
telemt_me_reconnect_attempts_total 2335
telemt_me_reconnect_success_total 1024
telemt_me_reader_eof_total 966
telemt_me_idle_close_by_peer_total 966
telemt_me_route_drop_no_conn_total 2249768
telemt_me_route_drop_channel_closed_total 130
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4815052
telemt_me_endpoint_quarantine_total 814
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 854
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
telemt_me_writers_active_current 42
telemt_desync_total 22964
telemt_desync_full_logged_total 7768
telemt_desync_suppressed_total 15196
telemt_desync_frames_bucket_total{bucket="1_2"} 5613
telemt_desync_frames_bucket_total{bucket="3_10"} 8806
telemt_desync_frames_bucket_total{bucket="gt_10"} 8545
telemt_pool_swap_total 123
telemt_pool_force_close_total 3579
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 406
telemt_me_draining_writers_reap_progress_total 38723
telemt_me_writer_removed_unexpected_total 953
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3289
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 36405
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3345
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 234
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 35144
telemt_me_writer_teardown_success_total{mode="normal"} 39694
telemt_me_writer_teardown_noop_total 38735
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 75647
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 77112
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 77595
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 78113
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 78351
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 78396
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 78429
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 78429
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 78429
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 78429
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 78429
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 78429
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 78429
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 32.314447
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 78429
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 406
telemt_me_refill_failed_total 73
telemt_me_writer_restored_same_endpoint_total 897
telemt_me_writer_restored_fallback_total 5
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 51
telemt_user_connections_total{user="hello"} 4809907
telemt_user_connections_current{user="hello"} 1949
telemt_user_octets_from_client{user="hello"} 135740886831 (126.42 GB)
telemt_user_octets_to_client{user="hello"} 2200974863575 (2.00 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 861
telemt_user_unique_ips_recent_window{user="hello"} 248
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 114741.3 (31h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20803138
telemt_connections_bad_total 1730682
telemt_connections_current 3114
telemt_connections_me_current 3114
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 629739
telemt_upstream_connect_attempt_total 203600
telemt_upstream_connect_success_total 185301
telemt_upstream_connect_fail_total 16472
telemt_upstream_connect_attempts_per_request{bucket="1"} 201773
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 130472
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 44654
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1224
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8951
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16472
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 65171
telemt_me_reconnect_success_total 2422
telemt_me_reader_eof_total 1508
telemt_me_idle_close_by_peer_total 1507
telemt_me_route_drop_no_conn_total 39617315
telemt_me_route_drop_channel_closed_total 128
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16741642
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 891
telemt_me_single_endpoint_outage_enter_total 144
telemt_me_single_endpoint_outage_exit_total 144
telemt_me_single_endpoint_outage_reconnect_attempt_total 297
telemt_me_single_endpoint_outage_reconnect_success_total 76
telemt_me_single_endpoint_quarantine_bypass_total 297
telemt_me_single_endpoint_shadow_rotate_total 902
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 68
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
telemt_desync_total 32511
telemt_desync_full_logged_total 9775
telemt_desync_suppressed_total 22736
telemt_desync_frames_bucket_total{bucket="1_2"} 7059
telemt_desync_frames_bucket_total{bucket="3_10"} 14418
telemt_desync_frames_bucket_total{bucket="gt_10"} 11034
telemt_pool_swap_total 119
telemt_pool_force_close_total 3836
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 835
telemt_me_draining_writers_reap_progress_total 36013
telemt_me_writer_removed_unexpected_total 2247
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4844
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 33161
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 24
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3302
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 534
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 32177
telemt_me_writer_teardown_success_total{mode="normal"} 38005
telemt_me_writer_teardown_noop_total 36040
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 67023
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 69591
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 70918
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 72647
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 73601
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 73943
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 74026
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 74028
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 74031
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 74036
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 74036
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 74040
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 74045
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 217.260984
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 74045
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 835
telemt_me_refill_failed_total 3809
telemt_me_writer_restored_same_endpoint_total 1645
telemt_me_writer_restored_fallback_total 21
telemt_me_no_writer_failfast_total 666
telemt_me_async_recovery_trigger_total 14678
telemt_me_writer_removed_unexpected_minus_restored_total 581
telemt_user_connections_total{user="hello"} 16876338
telemt_user_connections_current{user="hello"} 3114
telemt_user_octets_from_client{user="hello"} 240265816520 (223.76 GB)
telemt_user_octets_to_client{user="hello"} 1280376518455 (1.16 TB)
telemt_user_msgs_from_client{user="hello"} 398569
telemt_user_msgs_to_client{user="hello"} 788102
telemt_user_unique_ips_current{user="hello"} 1341
telemt_user_unique_ips_recent_window{user="hello"} 408
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 114708.7 (31h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6253773
telemt_connections_bad_total 604082
telemt_connections_current 2255
telemt_connections_me_current 2255
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 131759
telemt_upstream_connect_attempt_total 61659
telemt_upstream_connect_success_total 60961
telemt_upstream_connect_fail_total 595
telemt_upstream_connect_attempts_per_request{bucket="1"} 61556
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35284
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25319
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 357
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 595
telemt_me_reconnect_attempts_total 69833
telemt_me_reconnect_success_total 1839
telemt_me_reader_eof_total 1622
telemt_me_idle_close_by_peer_total 1621
telemt_me_route_drop_no_conn_total 2426742
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4851379
telemt_me_endpoint_quarantine_total 779
telemt_me_single_endpoint_outage_enter_total 23
telemt_me_single_endpoint_outage_exit_total 23
telemt_me_single_endpoint_outage_reconnect_attempt_total 24
telemt_me_single_endpoint_outage_reconnect_success_total 23
telemt_me_single_endpoint_quarantine_bypass_total 24
telemt_me_single_endpoint_shadow_rotate_total 872
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 34
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
telemt_me_writers_active_current 44
telemt_desync_total 24223
telemt_desync_full_logged_total 8493
telemt_desync_suppressed_total 15730
telemt_desync_frames_bucket_total{bucket="1_2"} 4740
telemt_desync_frames_bucket_total{bucket="3_10"} 9372
telemt_desync_frames_bucket_total{bucket="gt_10"} 10111
telemt_pool_swap_total 119
telemt_pool_force_close_total 3401
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 407
telemt_me_draining_writers_reap_progress_total 40596
telemt_me_writer_removed_unexpected_total 1658
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4119
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 38167
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3000
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 401
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 37195
telemt_me_writer_teardown_success_total{mode="normal"} 42286
telemt_me_writer_teardown_noop_total 40597
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 81564
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 82421
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 82713
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 82851
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 82880
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 82883
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 82883
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 82883
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 82883
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 82883
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 82883
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 82883
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 82883
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.560030
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 82883
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 407
telemt_me_refill_failed_total 4213
telemt_me_writer_restored_same_endpoint_total 1543
telemt_me_writer_restored_fallback_total 35
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7305
telemt_me_writer_removed_unexpected_minus_restored_total 80
telemt_user_connections_total{user="hello"} 4843761
telemt_user_connections_current{user="hello"} 2255
telemt_user_octets_from_client{user="hello"} 127050361120 (118.32 GB)
telemt_user_octets_to_client{user="hello"} 1996202070018 (1.82 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 1023
telemt_user_unique_ips_recent_window{user="hello"} 301
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 51544.5 (14h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4202729
telemt_connections_bad_total 178026
telemt_connections_current 1666
telemt_connections_me_current 1666
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 1680355
telemt_upstream_connect_attempt_total 30536
telemt_upstream_connect_success_total 30334
telemt_upstream_connect_fail_total 194
telemt_upstream_connect_attempts_per_request{bucket="1"} 30528
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18614
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11638
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 82
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 194
telemt_me_reconnect_attempts_total 45976
telemt_me_reconnect_success_total 1013
telemt_me_reader_eof_total 700
telemt_me_idle_close_by_peer_total 700
telemt_me_route_drop_no_conn_total 1052889
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2061197
telemt_me_endpoint_quarantine_total 379
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 50
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 50
telemt_me_single_endpoint_shadow_rotate_total 401
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 10
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
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 11059
telemt_desync_full_logged_total 3825
telemt_desync_suppressed_total 7234
telemt_desync_frames_bucket_total{bucket="1_2"} 2064
telemt_desync_frames_bucket_total{bucket="3_10"} 4237
telemt_desync_frames_bucket_total{bucket="gt_10"} 4758
telemt_pool_swap_total 56
telemt_pool_force_close_total 1647
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 149
telemt_me_draining_writers_reap_progress_total 19294
telemt_me_writer_removed_unexpected_total 772
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1679
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18415
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1440
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 207
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17647
telemt_me_writer_teardown_success_total{mode="normal"} 20094
telemt_me_writer_teardown_noop_total 19296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 38859
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 39145
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 39284
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 39390
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 39390
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 39390
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 39390
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 39390
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 39390
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 39390
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 39390
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 39390
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 39390
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.518590
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 39390
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 149
telemt_me_refill_failed_total 2612
telemt_me_writer_restored_same_endpoint_total 906
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4264
telemt_user_connections_total{user="hello"} 2064591
telemt_user_connections_current{user="hello"} 1666
telemt_user_octets_from_client{user="hello"} 56322317712 (52.45 GB)
telemt_user_octets_to_client{user="hello"} 889024311442 (827.97 GB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 782
telemt_user_unique_ips_recent_window{user="hello"} 307
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 32515.6 (9h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 229342
telemt_connections_bad_total 1848
telemt_connections_current 433
telemt_connections_me_current 433
telemt_handshake_timeouts_total 6005
telemt_upstream_connect_attempt_total 15778
telemt_upstream_connect_success_total 15740
telemt_upstream_connect_fail_total 36
telemt_upstream_connect_attempts_per_request{bucket="1"} 15776
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6643
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9014
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 83
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 36
telemt_me_reconnect_attempts_total 364
telemt_me_reconnect_success_total 204
telemt_me_reader_eof_total 210
telemt_me_idle_close_by_peer_total 210
telemt_me_route_drop_no_conn_total 63977
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 203368
telemt_me_endpoint_quarantine_total 319
telemt_me_single_endpoint_shadow_rotate_total 283
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 5
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
telemt_me_writers_active_current 42
telemt_desync_total 1142
telemt_desync_full_logged_total 307
telemt_desync_suppressed_total 835
telemt_desync_frames_bucket_total{bucket="1_2"} 416
telemt_desync_frames_bucket_total{bucket="3_10"} 434
telemt_desync_frames_bucket_total{bucket="gt_10"} 292
telemt_pool_swap_total 36
telemt_pool_force_close_total 781
telemt_me_writer_close_signal_drop_total 26
telemt_me_draining_writers_reap_progress_total 14262
telemt_me_writer_removed_unexpected_total 202
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 893
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13579
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 779
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13481
telemt_me_writer_teardown_success_total{mode="normal"} 14472
telemt_me_writer_teardown_noop_total 14262
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 28510
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 28706
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 28724
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 28734
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 28734
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 28734
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 28734
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 28734
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 28734
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 28734
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 28734
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 28734
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 28734
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.115742
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 28734
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 26
telemt_me_refill_failed_total 9
telemt_me_writer_restored_same_endpoint_total 185
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 16
telemt_user_connections_total{user="hello"} 203025
telemt_user_connections_current{user="hello"} 433
telemt_user_octets_from_client{user="hello"} 3492625420 (3.25 GB)
telemt_user_octets_to_client{user="hello"} 123004775460 (114.56 GB)
telemt_user_unique_ips_current{user="hello"} 185
telemt_user_unique_ips_recent_window{user="hello"} 53
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 114713.2 (31h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7576258
telemt_connections_bad_total 760450
telemt_connections_current 2307
telemt_connections_me_current 2307
telemt_handshake_timeouts_total 215923
telemt_upstream_connect_attempt_total 45265
telemt_upstream_connect_success_total 45101
telemt_upstream_connect_fail_total 127
telemt_upstream_connect_attempts_per_request{bucket="1"} 45228
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22344
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22716
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 127
telemt_me_reconnect_attempts_total 1654
telemt_me_reconnect_success_total 889
telemt_me_reader_eof_total 878
telemt_me_idle_close_by_peer_total 878
telemt_me_route_drop_no_conn_total 2163782
telemt_me_route_drop_channel_closed_total 52
telemt_me_route_drop_queue_full_total 23
telemt_me_route_drop_queue_full_profile_total{profile="high"} 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5645014
telemt_me_endpoint_quarantine_total 823
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 882
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
telemt_me_writers_active_current 44
telemt_desync_total 22087
telemt_desync_full_logged_total 7266
telemt_desync_suppressed_total 14821
telemt_desync_frames_bucket_total{bucket="1_2"} 5534
telemt_desync_frames_bucket_total{bucket="3_10"} 8018
telemt_desync_frames_bucket_total{bucket="gt_10"} 8535
telemt_pool_swap_total 127
telemt_pool_force_close_total 3390
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 399
telemt_me_draining_writers_reap_progress_total 40864
telemt_me_writer_removed_unexpected_total 844
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3184
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 38548
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3302
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 37474
telemt_me_writer_teardown_success_total{mode="normal"} 41732
telemt_me_writer_teardown_noop_total 40866
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 81220
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 82131
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 82310
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 82510
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 82598
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 82598
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 82598
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 82598
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 82598
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 82598
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 82598
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 82598
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 82598
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.741440
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 82598
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 399
telemt_me_refill_failed_total 40
telemt_me_writer_restored_same_endpoint_total 794
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 42
telemt_user_connections_total{user="hello"} 5619784
telemt_user_connections_current{user="hello"} 2307
telemt_user_octets_from_client{user="hello"} 111690501292 (104.02 GB)
telemt_user_octets_to_client{user="hello"} 2619231180412 (2.38 TB)
telemt_user_unique_ips_current{user="hello"} 970
telemt_user_unique_ips_recent_window{user="hello"} 274
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 114709.7 (31h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6568449
telemt_connections_bad_total 644916
telemt_connections_current 2363
telemt_connections_me_current 2363
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 177416
telemt_upstream_connect_attempt_total 61080
telemt_upstream_connect_success_total 60617
telemt_upstream_connect_fail_total 403
telemt_upstream_connect_attempts_per_request{bucket="1"} 61020
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35143
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24340
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 616
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 403
telemt_me_reconnect_attempts_total 5744
telemt_me_reconnect_success_total 1249
telemt_me_reader_eof_total 1121
telemt_me_idle_close_by_peer_total 1121
telemt_me_seq_mismatch_total 52
telemt_me_route_drop_no_conn_total 2217672
telemt_me_route_drop_channel_closed_total 191
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5013361
telemt_me_endpoint_quarantine_total 906
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 29
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 29
telemt_me_single_endpoint_shadow_rotate_total 880
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
telemt_me_writers_active_current 48
telemt_desync_total 20760
telemt_desync_full_logged_total 6929
telemt_desync_suppressed_total 13831
telemt_desync_frames_bucket_total{bucket="1_2"} 5287
telemt_desync_frames_bucket_total{bucket="3_10"} 7598
telemt_desync_frames_bucket_total{bucket="gt_10"} 7875
telemt_pool_swap_total 125
telemt_pool_force_close_total 3338
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 395
telemt_me_draining_writers_reap_progress_total 39410
telemt_me_writer_removed_unexpected_total 1132
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3737
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 36861
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3115
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 223
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 36072
telemt_me_writer_teardown_success_total{mode="normal"} 40598
telemt_me_writer_teardown_noop_total 39414
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 78319
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 79397
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 79778
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 79974
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 80012
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 80012
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 80012
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 80012
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 80012
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 80012
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 80012
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 80012
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 80012
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 11.402004
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 80012
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 395
telemt_me_refill_failed_total 259
telemt_me_writer_restored_same_endpoint_total 975
telemt_me_writer_restored_fallback_total 70
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 82
telemt_me_writer_removed_unexpected_minus_restored_total 87
telemt_user_connections_total{user="hello"} 5016154
telemt_user_connections_current{user="hello"} 2363
telemt_user_octets_from_client{user="hello"} 94594651533 (88.10 GB)
telemt_user_octets_to_client{user="hello"} 2149834463240 (1.96 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 992
telemt_user_unique_ips_recent_window{user="hello"} 258
```