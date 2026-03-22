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

# Server Metrics 2026-03-22 03:16:41 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 22219.2 (6h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 331221
telemt_connections_bad_total 22255
telemt_connections_current 965
telemt_connections_me_current 965
telemt_handshake_timeouts_total 18899
telemt_upstream_connect_attempt_total 9331
telemt_upstream_connect_success_total 9330
telemt_upstream_connect_attempts_per_request{bucket="1"} 9330
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3329
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5981
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 274
telemt_me_reconnect_success_total 148
telemt_me_reader_eof_total 144
telemt_me_idle_close_by_peer_total 144
telemt_me_route_drop_no_conn_total 62751
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 272761
telemt_me_endpoint_quarantine_total 178
telemt_me_single_endpoint_shadow_rotate_total 187
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 3
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
telemt_desync_total 2407
telemt_desync_full_logged_total 657
telemt_desync_suppressed_total 1750
telemt_desync_frames_bucket_total{bucket="1_2"} 812
telemt_desync_frames_bucket_total{bucket="3_10"} 903
telemt_desync_frames_bucket_total{bucket="gt_10"} 692
telemt_pool_swap_total 24
telemt_pool_force_close_total 629
telemt_me_writer_close_signal_drop_total 43
telemt_me_draining_writers_reap_progress_total 8409
telemt_me_writer_removed_unexpected_total 143
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 570
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 7973
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 624
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 7780
telemt_me_writer_teardown_success_total{mode="normal"} 8543
telemt_me_writer_teardown_noop_total 8410
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 16474
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 16763
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 16860
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 16919
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 16951
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 16953
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 16953
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 16953
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 16953
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 16953
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 16953
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 16953
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 16953
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.973815
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 16953
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 43
telemt_me_refill_failed_total 7
telemt_me_writer_restored_same_endpoint_total 134
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 272239
telemt_user_connections_current{user="hello"} 965
telemt_user_octets_from_client{user="hello"} 3261700660 (3.04 GB)
telemt_user_octets_to_client{user="hello"} 97215567248 (90.54 GB)
telemt_user_unique_ips_current{user="hello"} 401
telemt_user_unique_ips_recent_window{user="hello"} 123
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 35585.5 (9h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 816604
telemt_connections_bad_total 52398
telemt_connections_current 531
telemt_connections_me_current 531
telemt_handshake_timeouts_total 30021
telemt_upstream_connect_attempt_total 16627
telemt_upstream_connect_success_total 16369
telemt_upstream_connect_fail_total 235
telemt_upstream_connect_attempts_per_request{bucket="1"} 16604
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7197
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9126
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 235
telemt_me_reconnect_attempts_total 1381
telemt_me_reconnect_success_total 516
telemt_me_reader_eof_total 456
telemt_me_idle_close_by_peer_total 456
telemt_me_route_drop_no_conn_total 345222
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 645237
telemt_me_endpoint_quarantine_total 337
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 19
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 19
telemt_me_single_endpoint_shadow_rotate_total 289
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
telemt_desync_total 2787
telemt_desync_full_logged_total 1599
telemt_desync_suppressed_total 1188
telemt_desync_frames_bucket_total{bucket="1_2"} 589
telemt_desync_frames_bucket_total{bucket="3_10"} 1065
telemt_desync_frames_bucket_total{bucket="gt_10"} 1133
telemt_pool_swap_total 38
telemt_pool_force_close_total 1028
telemt_me_writer_close_signal_drop_total 72
telemt_me_draining_writers_reap_progress_total 14734
telemt_me_writer_removed_unexpected_total 433
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1232
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13945
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1006
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 22
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13706
telemt_me_writer_teardown_success_total{mode="normal"} 15177
telemt_me_writer_teardown_noop_total 14734
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 29379
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 29689
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 29805
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 29897
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 29909
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 29911
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 29911
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 29911
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 29911
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 29911
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 29911
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 29911
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 29911
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.779403
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 29911
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 72
telemt_me_refill_failed_total 45
telemt_me_writer_restored_same_endpoint_total 383
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 38
telemt_user_connections_total{user="hello"} 644306
telemt_user_connections_current{user="hello"} 531
telemt_user_octets_from_client{user="hello"} 10521253924 (9.80 GB)
telemt_user_octets_to_client{user="hello"} 229157521024 (213.42 GB)
telemt_user_unique_ips_current{user="hello"} 383
telemt_user_unique_ips_recent_window{user="hello"} 147
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 110445.6 (30h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7816053
telemt_connections_bad_total 640515
telemt_connections_current 1826
telemt_connections_me_current 1826
telemt_handshake_timeouts_total 256585
telemt_upstream_connect_attempt_total 41086
telemt_upstream_connect_success_total 41011
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 41018
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18546
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22287
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 172
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1595
telemt_me_reconnect_success_total 833
telemt_me_reader_eof_total 842
telemt_me_idle_close_by_peer_total 842
telemt_me_route_drop_no_conn_total 4546487
telemt_me_route_drop_channel_closed_total 66
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6319702
telemt_me_endpoint_quarantine_total 712
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 827
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
telemt_me_writers_active_current 47
telemt_desync_total 26589
telemt_desync_full_logged_total 8811
telemt_desync_suppressed_total 17778
telemt_desync_frames_bucket_total{bucket="1_2"} 5742
telemt_desync_frames_bucket_total{bucket="3_10"} 10379
telemt_desync_frames_bucket_total{bucket="gt_10"} 10468
telemt_pool_swap_total 119
telemt_pool_force_close_total 3936
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 607
telemt_me_draining_writers_reap_progress_total 37490
telemt_me_writer_removed_unexpected_total 810
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3135
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 34700
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3697
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 239
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 33554
telemt_me_writer_teardown_success_total{mode="normal"} 37835
telemt_me_writer_teardown_noop_total 37534
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 69064
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 70931
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 71941
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 73477
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 74513
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 75068
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 75358
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 75369
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 75369
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 75369
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 75369
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 75369
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 75369
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 160.794863
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 75369
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 607
telemt_me_refill_failed_total 40
telemt_me_writer_restored_same_endpoint_total 742
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 63
telemt_user_connections_total{user="hello"} 6311764
telemt_user_connections_current{user="hello"} 1826
telemt_user_octets_from_client{user="hello"} 107422749600 (100.05 GB)
telemt_user_octets_to_client{user="hello"} 2107317913804 (1.92 TB)
telemt_user_unique_ips_current{user="hello"} 909
telemt_user_unique_ips_recent_window{user="hello"} 224
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 110446.9 (30h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6462947
telemt_connections_bad_total 589671
telemt_connections_current 1752
telemt_connections_me_current 1752
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 214303
telemt_upstream_connect_attempt_total 45093
telemt_upstream_connect_success_total 44702
telemt_upstream_connect_fail_total 194
telemt_upstream_connect_attempts_per_request{bucket="1"} 44896
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22173
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21939
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 557
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 194
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 1952
telemt_me_reconnect_success_total 883
telemt_me_reader_eof_total 854
telemt_me_idle_close_by_peer_total 854
telemt_me_route_drop_no_conn_total 2267119
telemt_me_route_drop_channel_closed_total 264
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4821685
telemt_me_endpoint_quarantine_total 693
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 851
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
telemt_me_writers_active_current 43
telemt_desync_total 22753
telemt_desync_full_logged_total 7756
telemt_desync_suppressed_total 14997
telemt_desync_frames_bucket_total{bucket="1_2"} 5471
telemt_desync_frames_bucket_total{bucket="3_10"} 8844
telemt_desync_frames_bucket_total{bucket="gt_10"} 8438
telemt_pool_swap_total 120
telemt_pool_force_close_total 3571
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 367
telemt_me_draining_writers_reap_progress_total 36022
telemt_me_writer_removed_unexpected_total 839
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2990
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 33808
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3358
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 213
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 32451
telemt_me_writer_teardown_success_total{mode="normal"} 36798
telemt_me_writer_teardown_noop_total 36028
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 69494
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 71057
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 71630
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 72210
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 72621
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 72806
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 72826
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 72826
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 72826
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 72826
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 72826
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 72826
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 72826
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 48.453349
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 72826
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 367
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 772
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 59
telemt_user_connections_total{user="hello"} 4743776
telemt_user_connections_current{user="hello"} 1752
telemt_user_octets_from_client{user="hello"} 140838903821 (131.17 GB)
telemt_user_octets_to_client{user="hello"} 2246299267163 (2.04 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 847
telemt_user_unique_ips_recent_window{user="hello"} 187
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 110411.0 (30h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6335678
telemt_connections_bad_total 549664
telemt_connections_current 1353
telemt_connections_me_current 1353
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 205426
telemt_upstream_connect_attempt_total 51200
telemt_upstream_connect_success_total 50821
telemt_upstream_connect_fail_total 136
telemt_upstream_connect_attempts_per_request{bucket="1"} 50957
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25860
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23371
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 510
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1080
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 136
telemt_me_keepalive_timeout_total 58
telemt_me_reconnect_attempts_total 2080
telemt_me_reconnect_success_total 922
telemt_me_reader_eof_total 870
telemt_me_idle_close_by_peer_total 870
telemt_me_route_drop_no_conn_total 2160909
telemt_me_route_drop_channel_closed_total 125
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4707785
telemt_me_endpoint_quarantine_total 777
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 825
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
telemt_desync_total 22660
telemt_desync_full_logged_total 7630
telemt_desync_suppressed_total 15030
telemt_desync_frames_bucket_total{bucket="1_2"} 5533
telemt_desync_frames_bucket_total{bucket="3_10"} 8680
telemt_desync_frames_bucket_total{bucket="gt_10"} 8447
telemt_pool_swap_total 119
telemt_pool_force_close_total 3454
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 389
telemt_me_draining_writers_reap_progress_total 37097
telemt_me_writer_removed_unexpected_total 839
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3071
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 34882
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3239
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 215
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 33643
telemt_me_writer_teardown_success_total{mode="normal"} 37953
telemt_me_writer_teardown_noop_total 37109
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 72393
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 73824
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 74295
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 74796
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 75015
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 75042
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 75062
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 75062
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 75062
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 75062
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 75062
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 75062
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 75062
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 27.834628
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 75062
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 389
telemt_me_refill_failed_total 64
telemt_me_writer_restored_same_endpoint_total 800
telemt_me_writer_restored_fallback_total 5
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 34
telemt_user_connections_total{user="hello"} 4703275
telemt_user_connections_current{user="hello"} 1353
telemt_user_octets_from_client{user="hello"} 134441994103 (125.21 GB)
telemt_user_octets_to_client{user="hello"} 2157250363755 (1.96 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 713
telemt_user_unique_ips_recent_window{user="hello"} 161
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 110449.5 (30h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20519563
telemt_connections_bad_total 1654642
telemt_connections_current 2341
telemt_connections_me_current 2341
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 614735
telemt_upstream_connect_attempt_total 200054
telemt_upstream_connect_success_total 181938
telemt_upstream_connect_fail_total 16344
telemt_upstream_connect_attempts_per_request{bucket="1"} 198282
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 128574
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 43210
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1221
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8933
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16344
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 65030
telemt_me_reconnect_success_total 2344
telemt_me_reader_eof_total 1474
telemt_me_idle_close_by_peer_total 1473
telemt_me_route_drop_no_conn_total 39526283
telemt_me_route_drop_channel_closed_total 126
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16561552
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 864
telemt_me_single_endpoint_outage_enter_total 135
telemt_me_single_endpoint_outage_exit_total 135
telemt_me_single_endpoint_outage_reconnect_attempt_total 285
telemt_me_single_endpoint_outage_reconnect_success_total 70
telemt_me_single_endpoint_quarantine_bypass_total 285
telemt_me_single_endpoint_shadow_rotate_total 864
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 64
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
telemt_desync_total 32077
telemt_desync_full_logged_total 9645
telemt_desync_suppressed_total 22432
telemt_desync_frames_bucket_total{bucket="1_2"} 6946
telemt_desync_frames_bucket_total{bucket="3_10"} 14237
telemt_desync_frames_bucket_total{bucket="gt_10"} 10894
telemt_pool_swap_total 114
telemt_pool_force_close_total 3686
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 806
telemt_me_draining_writers_reap_progress_total 34662
telemt_me_writer_removed_unexpected_total 2172
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4663
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 31912
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 24
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3161
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 525
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 30976
telemt_me_writer_teardown_success_total{mode="normal"} 36575
telemt_me_writer_teardown_noop_total 34689
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 64409
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 66923
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 68213
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 69875
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 70820
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 71162
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 71245
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 71247
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 71250
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 71255
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 71255
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 71259
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 71264
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 215.248705
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 71264
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 806
telemt_me_refill_failed_total 3808
telemt_me_writer_restored_same_endpoint_total 1605
telemt_me_writer_restored_fallback_total 21
telemt_me_no_writer_failfast_total 666
telemt_me_async_recovery_trigger_total 14678
telemt_me_writer_removed_unexpected_minus_restored_total 546
telemt_user_connections_total{user="hello"} 16694642
telemt_user_connections_current{user="hello"} 2341
telemt_user_octets_from_client{user="hello"} 225529488324 (210.04 GB)
telemt_user_octets_to_client{user="hello"} 1223664172669 (1.11 TB)
telemt_user_msgs_from_client{user="hello"} 395497
telemt_user_msgs_to_client{user="hello"} 785476
telemt_user_unique_ips_current{user="hello"} 1101
telemt_user_unique_ips_recent_window{user="hello"} 270
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 110417.0 (30h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6085267
telemt_connections_bad_total 578454
telemt_connections_current 1808
telemt_connections_me_current 1808
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 128005
telemt_upstream_connect_attempt_total 59901
telemt_upstream_connect_success_total 59209
telemt_upstream_connect_fail_total 591
telemt_upstream_connect_attempts_per_request{bucket="1"} 59800
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34499
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24356
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 353
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 591
telemt_me_reconnect_attempts_total 69729
telemt_me_reconnect_success_total 1812
telemt_me_reader_eof_total 1595
telemt_me_idle_close_by_peer_total 1594
telemt_me_route_drop_no_conn_total 2397499
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4738824
telemt_me_endpoint_quarantine_total 749
telemt_me_single_endpoint_outage_enter_total 23
telemt_me_single_endpoint_outage_exit_total 23
telemt_me_single_endpoint_outage_reconnect_attempt_total 24
telemt_me_single_endpoint_outage_reconnect_success_total 23
telemt_me_single_endpoint_quarantine_bypass_total 24
telemt_me_single_endpoint_shadow_rotate_total 838
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
telemt_me_writers_active_current 43
telemt_desync_total 23585
telemt_desync_full_logged_total 8301
telemt_desync_suppressed_total 15284
telemt_desync_frames_bucket_total{bucket="1_2"} 4516
telemt_desync_frames_bucket_total{bucket="3_10"} 9134
telemt_desync_frames_bucket_total{bucket="gt_10"} 9935
telemt_pool_swap_total 114
telemt_pool_force_close_total 3268
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 397
telemt_me_draining_writers_reap_progress_total 38984
telemt_me_writer_removed_unexpected_total 1632
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3995
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 36653
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2867
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 401
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 35716
telemt_me_writer_teardown_success_total{mode="normal"} 40648
telemt_me_writer_teardown_noop_total 38985
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 78374
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 79202
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 79481
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 79601
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 79630
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 79633
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 79633
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 79633
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 79633
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 79633
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 79633
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 79633
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 79633
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.135696
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 79633
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 397
telemt_me_refill_failed_total 4209
telemt_me_writer_restored_same_endpoint_total 1521
telemt_me_writer_restored_fallback_total 35
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7305
telemt_me_writer_removed_unexpected_minus_restored_total 76
telemt_user_connections_total{user="hello"} 4731549
telemt_user_connections_current{user="hello"} 1808
telemt_user_octets_from_client{user="hello"} 125232212780 (116.63 GB)
telemt_user_octets_to_client{user="hello"} 1929939514826 (1.76 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 879
telemt_user_unique_ips_recent_window{user="hello"} 203
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 47252.8 (13h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4006625
telemt_connections_bad_total 154937
telemt_connections_current 1424
telemt_connections_me_current 1424
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 1625410
telemt_upstream_connect_attempt_total 28582
telemt_upstream_connect_success_total 28400
telemt_upstream_connect_fail_total 175
telemt_upstream_connect_attempts_per_request{bucket="1"} 28575
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17737
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10587
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 76
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 175
telemt_me_reconnect_attempts_total 45834
telemt_me_reconnect_success_total 979
telemt_me_reader_eof_total 663
telemt_me_idle_close_by_peer_total 663
telemt_me_route_drop_no_conn_total 1029231
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1962332
telemt_me_endpoint_quarantine_total 355
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 50
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 50
telemt_me_single_endpoint_shadow_rotate_total 366
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 9
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
telemt_me_writers_active_current 46
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 10580
telemt_desync_full_logged_total 3658
telemt_desync_suppressed_total 6922
telemt_desync_frames_bucket_total{bucket="1_2"} 1911
telemt_desync_frames_bucket_total{bucket="3_10"} 4060
telemt_desync_frames_bucket_total{bucket="gt_10"} 4609
telemt_pool_swap_total 51
telemt_pool_force_close_total 1526
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 139
telemt_me_draining_writers_reap_progress_total 17538
telemt_me_writer_removed_unexpected_total 736
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1568
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16733
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1320
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 206
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16012
telemt_me_writer_teardown_success_total{mode="normal"} 18301
telemt_me_writer_teardown_noop_total 17540
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 35311
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 35596
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 35735
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 35841
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 35841
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 35841
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 35841
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 35841
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 35841
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 35841
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 35841
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 35841
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 35841
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.494262
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 35841
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 139
telemt_me_refill_failed_total 2606
telemt_me_writer_restored_same_endpoint_total 877
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4264
telemt_user_connections_total{user="hello"} 1965875
telemt_user_connections_current{user="hello"} 1424
telemt_user_octets_from_client{user="hello"} 54703870880 (50.95 GB)
telemt_user_octets_to_client{user="hello"} 833388435398 (776.15 GB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 738
telemt_user_unique_ips_recent_window{user="hello"} 164
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 28223.9 (7h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 205661
telemt_connections_bad_total 1757
telemt_connections_current 389
telemt_connections_me_current 389
telemt_handshake_timeouts_total 5610
telemt_upstream_connect_attempt_total 13604
telemt_upstream_connect_success_total 13572
telemt_upstream_connect_fail_total 30
telemt_upstream_connect_attempts_per_request{bucket="1"} 13602
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5742
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7751
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 79
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 30
telemt_me_reconnect_attempts_total 294
telemt_me_reconnect_success_total 171
telemt_me_reader_eof_total 176
telemt_me_idle_close_by_peer_total 176
telemt_me_route_drop_no_conn_total 56948
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 181563
telemt_me_endpoint_quarantine_total 283
telemt_me_single_endpoint_shadow_rotate_total 247
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
telemt_me_writers_active_current 43
telemt_desync_total 1048
telemt_desync_full_logged_total 266
telemt_desync_suppressed_total 782
telemt_desync_frames_bucket_total{bucket="1_2"} 393
telemt_desync_frames_bucket_total{bucket="3_10"} 392
telemt_desync_frames_bucket_total{bucket="gt_10"} 263
telemt_pool_swap_total 31
telemt_pool_force_close_total 692
telemt_me_writer_close_signal_drop_total 24
telemt_me_draining_writers_reap_progress_total 12312
telemt_me_writer_removed_unexpected_total 169
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 792
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 11696
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 690
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 11620
telemt_me_writer_teardown_success_total{mode="normal"} 12488
telemt_me_writer_teardown_noop_total 12312
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 24588
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 24772
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 24790
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 24800
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 24800
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 24800
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 24800
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 24800
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 24800
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 24800
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 24800
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 24800
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 24800
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.047004
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 24800
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 24
telemt_me_refill_failed_total 7
telemt_me_writer_restored_same_endpoint_total 155
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 13
telemt_user_connections_total{user="hello"} 181241
telemt_user_connections_current{user="hello"} 389
telemt_user_octets_from_client{user="hello"} 3229908896 (3.01 GB)
telemt_user_octets_to_client{user="hello"} 113927775380 (106.10 GB)
telemt_user_unique_ips_current{user="hello"} 166
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 110421.5 (30h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7406563
telemt_connections_bad_total 745609
telemt_connections_current 1788
telemt_connections_me_current 1788
telemt_handshake_timeouts_total 210681
telemt_upstream_connect_attempt_total 43361
telemt_upstream_connect_success_total 43202
telemt_upstream_connect_fail_total 122
telemt_upstream_connect_attempts_per_request{bucket="1"} 43324
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21400
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21761
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 122
telemt_me_reconnect_attempts_total 1592
telemt_me_reconnect_success_total 857
telemt_me_reader_eof_total 842
telemt_me_idle_close_by_peer_total 842
telemt_me_route_drop_no_conn_total 2136007
telemt_me_route_drop_channel_closed_total 52
telemt_me_route_drop_queue_full_total 23
telemt_me_route_drop_queue_full_profile_total{profile="high"} 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5525528
telemt_me_endpoint_quarantine_total 779
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 852
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
telemt_desync_total 21708
telemt_desync_full_logged_total 7110
telemt_desync_suppressed_total 14598
telemt_desync_frames_bucket_total{bucket="1_2"} 5453
telemt_desync_frames_bucket_total{bucket="3_10"} 7861
telemt_desync_frames_bucket_total{bucket="gt_10"} 8394
telemt_pool_swap_total 122
telemt_pool_force_close_total 3260
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 392
telemt_me_draining_writers_reap_progress_total 39131
telemt_me_writer_removed_unexpected_total 811
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3062
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 36901
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3172
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 35871
telemt_me_writer_teardown_success_total{mode="normal"} 39963
telemt_me_writer_teardown_noop_total 39133
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 77731
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 78630
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 78808
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 79008
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 79096
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 79096
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 79096
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 79096
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 79096
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 79096
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 79096
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 79096
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 79096
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.679454
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 79096
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 392
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 766
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 37
telemt_user_connections_total{user="hello"} 5500496
telemt_user_connections_current{user="hello"} 1788
telemt_user_octets_from_client{user="hello"} 110207918732 (102.64 GB)
telemt_user_octets_to_client{user="hello"} 2563600407332 (2.33 TB)
telemt_user_unique_ips_current{user="hello"} 832
telemt_user_unique_ips_recent_window{user="hello"} 187
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 110417.9 (30h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6400941
telemt_connections_bad_total 632062
telemt_connections_current 1773
telemt_connections_me_current 1773
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 174181
telemt_upstream_connect_attempt_total 59168
telemt_upstream_connect_success_total 58723
telemt_upstream_connect_fail_total 386
telemt_upstream_connect_attempts_per_request{bucket="1"} 59109
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34160
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23429
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 616
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 386
telemt_me_reconnect_attempts_total 5593
telemt_me_reconnect_success_total 1192
telemt_me_reader_eof_total 1077
telemt_me_idle_close_by_peer_total 1077
telemt_me_seq_mismatch_total 49
telemt_me_route_drop_no_conn_total 2189131
telemt_me_route_drop_channel_closed_total 189
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4892971
telemt_me_endpoint_quarantine_total 873
telemt_me_single_endpoint_outage_enter_total 28
telemt_me_single_endpoint_outage_exit_total 28
telemt_me_single_endpoint_outage_reconnect_attempt_total 28
telemt_me_single_endpoint_outage_reconnect_success_total 26
telemt_me_single_endpoint_quarantine_bypass_total 28
telemt_me_single_endpoint_shadow_rotate_total 846
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
telemt_me_writers_active_current 43
telemt_desync_total 20291
telemt_desync_full_logged_total 6764
telemt_desync_suppressed_total 13527
telemt_desync_frames_bucket_total{bucket="1_2"} 5199
telemt_desync_frames_bucket_total{bucket="3_10"} 7401
telemt_desync_frames_bucket_total{bucket="gt_10"} 7691
telemt_pool_swap_total 120
telemt_pool_force_close_total 3219
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 383
telemt_me_draining_writers_reap_progress_total 37690
telemt_me_writer_removed_unexpected_total 1088
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3595
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 35236
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2996
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 223
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 34471
telemt_me_writer_teardown_success_total{mode="normal"} 38831
telemt_me_writer_teardown_noop_total 37694
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 74880
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 75937
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 76292
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 76487
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 76525
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 76525
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 76525
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 76525
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 76525
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 76525
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 76525
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 76525
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 76525
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 11.100003
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 76525
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 383
telemt_me_refill_failed_total 254
telemt_me_writer_restored_same_endpoint_total 932
telemt_me_writer_restored_fallback_total 66
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 76
telemt_me_writer_removed_unexpected_minus_restored_total 90
telemt_user_connections_total{user="hello"} 4895921
telemt_user_connections_current{user="hello"} 1773
telemt_user_octets_from_client{user="hello"} 92547223997 (86.19 GB)
telemt_user_octets_to_client{user="hello"} 2092333573508 (1.90 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 801
telemt_user_unique_ips_recent_window{user="hello"} 196
```