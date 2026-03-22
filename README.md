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

# Server Metrics 2026-03-22 17:00:06 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 71623.5 (19h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2558813
telemt_connections_bad_total 138221
telemt_connections_current 1952
telemt_connections_me_current 1952
telemt_handshake_timeouts_total 89678
telemt_upstream_connect_attempt_total 26412
telemt_upstream_connect_success_total 26411
telemt_upstream_connect_attempts_per_request{bucket="1"} 26411
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9179
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17152
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 59
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 150
telemt_me_reconnect_attempts_total 1066
telemt_me_reconnect_success_total 456
telemt_me_reader_eof_total 458
telemt_me_idle_close_by_peer_total 458
telemt_me_route_drop_no_conn_total 2058412
telemt_me_route_drop_channel_closed_total 863
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2180661
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_endpoint_quarantine_total 485
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 562
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
telemt_me_writers_active_current 49
telemt_desync_total 10300
telemt_desync_full_logged_total 3248
telemt_desync_suppressed_total 7052
telemt_desync_frames_bucket_total{bucket="1_2"} 2753
telemt_desync_frames_bucket_total{bucket="3_10"} 3848
telemt_desync_frames_bucket_total{bucket="gt_10"} 3699
telemt_pool_swap_total 79
telemt_pool_force_close_total 2457
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 482
telemt_me_draining_writers_reap_progress_total 24107
telemt_me_writer_removed_unexpected_total 444
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1760
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22568
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2406
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 51
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21650
telemt_me_writer_teardown_success_total{mode="normal"} 24328
telemt_me_writer_teardown_noop_total 24113
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 39127
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 40875
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 42536
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 45378
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 47285
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 48166
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 48437
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 48441
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 48441
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 48441
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 48441
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 48441
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 48441
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 231.891548
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 48441
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 482
telemt_me_refill_failed_total 32
telemt_me_writer_restored_same_endpoint_total 404
telemt_me_writer_removed_unexpected_minus_restored_total 40
telemt_user_connections_total{user="hello"} 2177111
telemt_user_connections_current{user="hello"} 1952
telemt_user_octets_from_client{user="hello"} 32606475252 (30.37 GB)
telemt_user_octets_to_client{user="hello"} 578297788564 (538.58 GB)
telemt_user_unique_ips_current{user="hello"} 670
telemt_user_unique_ips_recent_window{user="hello"} 414
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 84989.8 (23h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3637685
telemt_connections_bad_total 329682
telemt_connections_current 676
telemt_connections_me_current 676
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 90864
telemt_upstream_connect_attempt_total 53074
telemt_upstream_connect_success_total 52414
telemt_upstream_connect_fail_total 580
telemt_upstream_connect_attempts_per_request{bucket="1"} 52994
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30295
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21947
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 172
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 580
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 6127
telemt_me_reconnect_success_total 2230
telemt_me_reader_eof_total 2164
telemt_me_idle_close_by_peer_total 2164
telemt_me_route_drop_no_conn_total 3542457
telemt_me_route_drop_channel_closed_total 36
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2884959
telemt_me_endpoint_quarantine_total 680
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 37
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 656
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 36
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
telemt_desync_total 11326
telemt_desync_full_logged_total 6317
telemt_desync_suppressed_total 5009
telemt_desync_frames_bucket_total{bucket="1_2"} 2639
telemt_desync_frames_bucket_total{bucket="3_10"} 4442
telemt_desync_frames_bucket_total{bucket="gt_10"} 4245
telemt_pool_swap_total 80
telemt_pool_force_close_total 2404
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 203
telemt_me_draining_writers_reap_progress_total 33898
telemt_me_writer_removed_unexpected_total 2117
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4063
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 31960
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2044
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 360
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 31494
telemt_me_writer_teardown_success_total{mode="normal"} 36023
telemt_me_writer_teardown_noop_total 33898
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 68198
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 69276
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 69549
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 69855
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 69906
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 69919
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 69921
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 69921
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 69921
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 69921
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 69921
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 69921
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 69921
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 13.129669
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 69921
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 203
telemt_me_refill_failed_total 153
telemt_me_writer_restored_same_endpoint_total 1930
telemt_me_writer_restored_fallback_total 25
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 162
telemt_user_connections_total{user="hello"} 2896199
telemt_user_connections_current{user="hello"} 676
telemt_user_octets_from_client{user="hello"} 36405971519 (33.91 GB)
telemt_user_octets_to_client{user="hello"} 653099272002 (608.25 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 427
telemt_user_unique_ips_recent_window{user="hello"} 228
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 159849.7 (44h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15432615
telemt_connections_bad_total 1455501
telemt_connections_current 2221
telemt_connections_me_current 2221
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 376442
telemt_upstream_connect_attempt_total 72027
telemt_upstream_connect_success_total 71931
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 71948
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36137
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34111
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1676
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2680
telemt_me_reconnect_success_total 1371
telemt_me_reader_eof_total 1310
telemt_me_idle_close_by_peer_total 1308
telemt_me_route_drop_no_conn_total 13831236
telemt_me_route_drop_channel_closed_total 139
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12318935
telemt_me_endpoint_quarantine_total 1007
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1191
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
telemt_desync_total 50293
telemt_desync_full_logged_total 15799
telemt_desync_suppressed_total 34494
telemt_desync_frames_bucket_total{bucket="1_2"} 11230
telemt_desync_frames_bucket_total{bucket="3_10"} 19640
telemt_desync_frames_bucket_total{bucket="gt_10"} 19423
telemt_pool_swap_total 172
telemt_pool_force_close_total 5849
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 943
telemt_me_draining_writers_reap_progress_total 52579
telemt_me_writer_removed_unexpected_total 1264
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4585
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 48549
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 42
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5389
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 460
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 46730
telemt_me_writer_teardown_success_total{mode="normal"} 53134
telemt_me_writer_teardown_noop_total 52629
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 95575
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 98853
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 100457
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 102624
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 104180
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 105166
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 105724
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 105754
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 105755
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 105759
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 105761
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 105763
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 105763
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 301.811725
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 105763
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 943
telemt_me_refill_failed_total 72
telemt_me_writer_restored_same_endpoint_total 1177
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 80
telemt_user_connections_total{user="hello"} 12320015
telemt_user_connections_current{user="hello"} 2221
telemt_user_octets_from_client{user="hello"} 176008599073 (163.92 GB)
telemt_user_octets_to_client{user="hello"} 3194451586623 (2.91 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 896
telemt_user_unique_ips_recent_window{user="hello"} 241
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 159851.1 (44h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11131629
telemt_connections_bad_total 1082412
telemt_connections_current 1715
telemt_connections_me_current 1715
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 332205
telemt_upstream_connect_attempt_total 84233
telemt_upstream_connect_success_total 83075
telemt_upstream_connect_fail_total 834
telemt_upstream_connect_attempts_per_request{bucket="1"} 83909
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 45245
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33978
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 157
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3695
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 834
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 182
telemt_me_reconnect_attempts_total 3950
telemt_me_reconnect_success_total 1613
telemt_me_reader_eof_total 1485
telemt_me_idle_close_by_peer_total 1485
telemt_me_route_drop_no_conn_total 4377669
telemt_me_route_drop_channel_closed_total 481
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8300045
telemt_me_endpoint_quarantine_total 1007
telemt_me_single_endpoint_outage_enter_total 27
telemt_me_single_endpoint_outage_exit_total 27
telemt_me_single_endpoint_outage_reconnect_attempt_total 32
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 32
telemt_me_single_endpoint_shadow_rotate_total 1208
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 43
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
telemt_desync_total 36882
telemt_desync_full_logged_total 12402
telemt_desync_suppressed_total 24480
telemt_desync_frames_bucket_total{bucket="1_2"} 9053
telemt_desync_frames_bucket_total{bucket="3_10"} 14219
telemt_desync_frames_bucket_total{bucket="gt_10"} 13610
telemt_pool_swap_total 170
telemt_pool_force_close_total 5273
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 667
telemt_me_draining_writers_reap_progress_total 50874
telemt_me_writer_removed_unexpected_total 1513
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4687
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 47561
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 18
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4795
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 478
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 45601
telemt_me_writer_teardown_success_total{mode="normal"} 52248
telemt_me_writer_teardown_noop_total 50892
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 96884
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 99839
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 100916
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 102010
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 102724
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 103055
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 103130
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 103132
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 103138
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 103140
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 103140
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 103140
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 103140
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 99.291459
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 103140
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 667
telemt_me_refill_failed_total 126
telemt_me_writer_restored_same_endpoint_total 1375
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 124
telemt_user_connections_total{user="hello"} 8238639
telemt_user_connections_current{user="hello"} 1715
telemt_user_octets_from_client{user="hello"} 205823695129 (191.69 GB)
telemt_user_octets_to_client{user="hello"} 3711840149806 (3.38 TB)
telemt_user_msgs_from_client{user="hello"} 113340
telemt_user_msgs_to_client{user="hello"} 116189
telemt_user_unique_ips_current{user="hello"} 670
telemt_user_unique_ips_recent_window{user="hello"} 217
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 159815.1 (44h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10515603
telemt_connections_bad_total 907801
telemt_connections_current 1144
telemt_connections_me_current 1144
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 336214
telemt_upstream_connect_attempt_total 69458
telemt_upstream_connect_success_total 68474
telemt_upstream_connect_fail_total 182
telemt_upstream_connect_attempts_per_request{bucket="1"} 68656
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32527
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32493
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1366
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2088
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 182
telemt_me_keepalive_timeout_total 1383
telemt_me_reconnect_attempts_total 4753
telemt_me_reconnect_success_total 1919
telemt_me_reader_eof_total 1670
telemt_me_idle_close_by_peer_total 1669
telemt_me_route_drop_no_conn_total 5152648
telemt_me_route_drop_channel_closed_total 365
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7935012
telemt_me_endpoint_quarantine_total 1093
telemt_me_single_endpoint_outage_enter_total 32
telemt_me_single_endpoint_outage_exit_total 32
telemt_me_single_endpoint_outage_reconnect_attempt_total 33
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 33
telemt_me_single_endpoint_shadow_rotate_total 1177
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 56
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
telemt_desync_total 36365
telemt_desync_full_logged_total 12037
telemt_desync_suppressed_total 24328
telemt_desync_frames_bucket_total{bucket="1_2"} 9204
telemt_desync_frames_bucket_total{bucket="3_10"} 13904
telemt_desync_frames_bucket_total{bucket="gt_10"} 13257
telemt_pool_swap_total 167
telemt_pool_force_close_total 5215
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 685
telemt_me_draining_writers_reap_progress_total 51205
telemt_me_writer_removed_unexpected_total 1812
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5143
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 47787
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4673
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 542
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 45990
telemt_me_writer_teardown_success_total{mode="normal"} 52930
telemt_me_writer_teardown_noop_total 51276
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 98721
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 101230
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 102131
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 103156
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 103727
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 103939
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 104067
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 104098
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 104106
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 104119
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 104152
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 104155
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 104206
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3171.810462
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 104206
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 685
telemt_me_refill_failed_total 150
telemt_me_writer_restored_same_endpoint_total 1658
telemt_me_writer_restored_fallback_total 10
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 144
telemt_user_connections_total{user="hello"} 7927873
telemt_user_connections_current{user="hello"} 1144
telemt_user_octets_from_client{user="hello"} 183264847589 (170.68 GB)
telemt_user_octets_to_client{user="hello"} 3296562709413 (3.00 TB)
telemt_user_msgs_from_client{user="hello"} 46485
telemt_user_msgs_to_client{user="hello"} 113805
telemt_user_unique_ips_current{user="hello"} 445
telemt_user_unique_ips_recent_window{user="hello"} 173
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 30095.1 (8h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10267763
telemt_connections_bad_total 626134
telemt_connections_current 1734
telemt_connections_me_current 1734
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 195354
telemt_upstream_connect_attempt_total 40540
telemt_upstream_connect_success_total 38479
telemt_upstream_connect_fail_total 1475
telemt_upstream_connect_attempts_per_request{bucket="1"} 39954
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19911
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11265
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1389
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5914
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1475
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 6077
telemt_me_reconnect_success_total 774
telemt_me_reader_eof_total 475
telemt_me_idle_close_by_peer_total 475
telemt_me_route_drop_no_conn_total 24977140
telemt_me_route_drop_channel_closed_total 50
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8540473
telemt_me_endpoint_quarantine_total 186
telemt_me_single_endpoint_outage_enter_total 58
telemt_me_single_endpoint_outage_exit_total 58
telemt_me_single_endpoint_outage_reconnect_attempt_total 109
telemt_me_single_endpoint_outage_reconnect_success_total 31
telemt_me_single_endpoint_quarantine_bypass_total 109
telemt_me_single_endpoint_shadow_rotate_total 241
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 43
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 13396
telemt_desync_full_logged_total 3469
telemt_desync_suppressed_total 9927
telemt_desync_frames_bucket_total{bucket="1_2"} 2413
telemt_desync_frames_bucket_total{bucket="3_10"} 5443
telemt_desync_frames_bucket_total{bucket="gt_10"} 5540
telemt_pool_swap_total 29
telemt_pool_force_close_total 1126
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 376
telemt_me_draining_writers_reap_progress_total 8331
telemt_me_writer_removed_unexpected_total 679
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1379
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 7596
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 844
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 282
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 7205
telemt_me_writer_teardown_success_total{mode="normal"} 8975
telemt_me_writer_teardown_noop_total 8336
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 14491
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 15840
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 16318
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 16913
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 17186
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 17284
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 17311
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 17311
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 17311
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 17311
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 17311
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 17311
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 17311
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 37.524721
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 17311
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 376
telemt_me_refill_failed_total 293
telemt_me_writer_restored_same_endpoint_total 518
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 86
telemt_me_async_recovery_trigger_total 3059
telemt_me_writer_removed_unexpected_minus_restored_total 157
telemt_user_connections_total{user="hello"} 8562227
telemt_user_connections_current{user="hello"} 1734
telemt_user_octets_from_client{user="hello"} 66420382035 (61.86 GB)
telemt_user_octets_to_client{user="hello"} 332274985977 (309.46 GB)
telemt_user_msgs_from_client{user="hello"} 57283
telemt_user_msgs_to_client{user="hello"} 45481
telemt_user_unique_ips_current{user="hello"} 679
telemt_user_unique_ips_recent_window{user="hello"} 267
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 159821.8 (44h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10315969
telemt_connections_bad_total 866956
telemt_connections_current 2009
telemt_connections_me_current 2009
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 228781
telemt_upstream_connect_attempt_total 98223
telemt_upstream_connect_success_total 97208
telemt_upstream_connect_fail_total 864
telemt_upstream_connect_attempts_per_request{bucket="1"} 98072
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 59956
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35704
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1310
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 864
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 72056
telemt_me_reconnect_success_total 2637
telemt_me_reader_eof_total 2340
telemt_me_idle_close_by_peer_total 2338
telemt_me_route_drop_no_conn_total 5082489
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8136250
telemt_me_endpoint_quarantine_total 1076
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 39
telemt_me_single_endpoint_outage_reconnect_success_total 37
telemt_me_single_endpoint_quarantine_bypass_total 39
telemt_me_single_endpoint_shadow_rotate_total 1191
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 49
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
telemt_desync_total 42459
telemt_desync_full_logged_total 14492
telemt_desync_suppressed_total 27967
telemt_desync_frames_bucket_total{bucket="1_2"} 8621
telemt_desync_frames_bucket_total{bucket="3_10"} 16410
telemt_desync_frames_bucket_total{bucket="gt_10"} 17428
telemt_pool_swap_total 163
telemt_pool_force_close_total 4850
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 613
telemt_me_draining_writers_reap_progress_total 54353
telemt_me_writer_removed_unexpected_total 2383
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5805
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 50952
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4165
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 685
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 49503
telemt_me_writer_teardown_success_total{mode="normal"} 56757
telemt_me_writer_teardown_noop_total 54354
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 109111
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 110411
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 110795
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 111067
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 111101
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 111104
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 111104
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 111107
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 111111
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 111111
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 111111
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 111111
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 111111
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 16.524739
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 111111
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 613
telemt_me_refill_failed_total 4279
telemt_me_writer_restored_same_endpoint_total 2209
telemt_me_writer_restored_fallback_total 45
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7365
telemt_me_writer_removed_unexpected_minus_restored_total 129
telemt_user_connections_total{user="hello"} 8140092
telemt_user_connections_current{user="hello"} 2009
telemt_user_octets_from_client{user="hello"} 184048069569 (171.41 GB)
telemt_user_octets_to_client{user="hello"} 3068134193088 (2.79 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 760
telemt_user_unique_ips_recent_window{user="hello"} 271
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 96657.9 (26h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10752635
telemt_connections_bad_total 406409
telemt_connections_current 1542
telemt_connections_me_current 1542
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4502163
telemt_upstream_connect_attempt_total 46437
telemt_upstream_connect_success_total 46097
telemt_upstream_connect_fail_total 331
telemt_upstream_connect_attempts_per_request{bucket="1"} 46428
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25777
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20163
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 157
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 331
telemt_me_reconnect_attempts_total 48171
telemt_me_reconnect_success_total 1528
telemt_me_reader_eof_total 1195
telemt_me_idle_close_by_peer_total 1194
telemt_me_route_drop_no_conn_total 3935764
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5157995
telemt_me_endpoint_quarantine_total 626
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 58
telemt_me_single_endpoint_outage_reconnect_success_total 18
telemt_me_single_endpoint_quarantine_bypass_total 58
telemt_me_single_endpoint_shadow_rotate_total 729
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 21
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
telemt_desync_total 28389
telemt_desync_full_logged_total 9592
telemt_desync_suppressed_total 18797
telemt_desync_frames_bucket_total{bucket="1_2"} 5720
telemt_desync_frames_bucket_total{bucket="3_10"} 11188
telemt_desync_frames_bucket_total{bucket="gt_10"} 11481
telemt_pool_swap_total 102
telemt_pool_force_close_total 3135
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 324
telemt_me_draining_writers_reap_progress_total 33349
telemt_me_writer_removed_unexpected_total 1257
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2992
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 31645
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2716
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 419
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 30214
telemt_me_writer_teardown_success_total{mode="normal"} 34637
telemt_me_writer_teardown_noop_total 33356
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 66844
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 67504
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 67769
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 67993
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 67993
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 67993
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 67993
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 67993
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 67993
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 67993
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 67993
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 67993
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 67993
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.945783
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 67993
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 324
telemt_me_refill_failed_total 2711
telemt_me_writer_restored_same_endpoint_total 1358
telemt_me_writer_restored_fallback_total 15
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4328
telemt_user_connections_total{user="hello"} 5151391
telemt_user_connections_current{user="hello"} 1542
telemt_user_octets_from_client{user="hello"} 111245334084 (103.61 GB)
telemt_user_octets_to_client{user="hello"} 1948166375814 (1.77 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 568
telemt_user_unique_ips_recent_window{user="hello"} 225
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 77628.8 (21h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1067108
telemt_connections_bad_total 16057
telemt_connections_current 1141
telemt_connections_me_current 1141
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 20195
telemt_upstream_connect_attempt_total 37893
telemt_upstream_connect_success_total 37787
telemt_upstream_connect_fail_total 85
telemt_upstream_connect_attempts_per_request{bucket="1"} 37872
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17132
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20096
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 559
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 85
telemt_me_reconnect_attempts_total 1733
telemt_me_reconnect_success_total 725
telemt_me_reader_eof_total 700
telemt_me_idle_close_by_peer_total 700
telemt_me_route_drop_no_conn_total 372971
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 950509
telemt_me_endpoint_quarantine_total 660
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 641
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 15
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
telemt_desync_total 5411
telemt_desync_full_logged_total 1662
telemt_desync_suppressed_total 3749
telemt_desync_frames_bucket_total{bucket="1_2"} 1263
telemt_desync_frames_bucket_total{bucket="3_10"} 2143
telemt_desync_frames_bucket_total{bucket="gt_10"} 2005
telemt_pool_swap_total 83
telemt_pool_force_close_total 2117
telemt_me_writer_close_signal_drop_total 121
telemt_me_draining_writers_reap_progress_total 31411
telemt_me_writer_removed_unexpected_total 676
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2435
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 29678
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2035
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 82
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 29294
telemt_me_writer_teardown_success_total{mode="normal"} 32113
telemt_me_writer_teardown_noop_total 31414
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 62845
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 63332
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 63496
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 63527
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 63527
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 63527
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 63527
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 63527
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 63527
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 63527
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 63527
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 63527
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 63527
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.781106
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 63527
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 121
telemt_me_refill_failed_total 55
telemt_me_writer_restored_same_endpoint_total 616
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 946992
telemt_user_connections_current{user="hello"} 1141
telemt_user_octets_from_client{user="hello"} 17365519757 (16.17 GB)
telemt_user_octets_to_client{user="hello"} 412548759211 (384.22 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 408
telemt_user_unique_ips_recent_window{user="hello"} 307
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 159826.3 (44h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12592394
telemt_connections_bad_total 1460199
telemt_connections_current 1854
telemt_connections_me_current 1854
telemt_handshake_timeouts_total 348997
telemt_upstream_connect_attempt_total 60057
telemt_upstream_connect_success_total 59792
telemt_upstream_connect_fail_total 185
telemt_upstream_connect_attempts_per_request{bucket="1"} 59977
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29498
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30214
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 78
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 185
telemt_me_reconnect_attempts_total 2370
telemt_me_reconnect_success_total 1249
telemt_me_reader_eof_total 1214
telemt_me_idle_close_by_peer_total 1214
telemt_me_route_drop_no_conn_total 4206078
telemt_me_route_drop_channel_closed_total 121
telemt_me_route_drop_queue_full_total 37
telemt_me_route_drop_queue_full_profile_total{profile="high"} 37
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9524288
telemt_me_endpoint_quarantine_total 1072
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1194
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
telemt_desync_total 39090
telemt_desync_full_logged_total 12759
telemt_desync_suppressed_total 26331
telemt_desync_frames_bucket_total{bucket="1_2"} 9296
telemt_desync_frames_bucket_total{bucket="3_10"} 14481
telemt_desync_frames_bucket_total{bucket="gt_10"} 15313
telemt_pool_swap_total 177
telemt_pool_force_close_total 4891
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 624
telemt_me_draining_writers_reap_progress_total 54064
telemt_me_writer_removed_unexpected_total 1166
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4445
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 50819
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4717
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 49173
telemt_me_writer_teardown_success_total{mode="normal"} 55264
telemt_me_writer_teardown_noop_total 54066
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 106913
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 108516
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 108873
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 109197
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 109317
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 109330
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 109330
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 109330
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 109330
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 109330
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 109330
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 109330
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 109330
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 18.356708
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 109330
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 624
telemt_me_refill_failed_total 59
telemt_me_writer_restored_same_endpoint_total 1092
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 62
telemt_user_connections_total{user="hello"} 9493471
telemt_user_connections_current{user="hello"} 1854
telemt_user_octets_from_client{user="hello"} 186253915192 (173.46 GB)
telemt_user_octets_to_client{user="hello"} 4191966848328 (3.81 TB)
telemt_user_unique_ips_current{user="hello"} 684
telemt_user_unique_ips_recent_window{user="hello"} 221
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 159822.9 (44h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10919195
telemt_connections_bad_total 1219735
telemt_connections_current 1489
telemt_connections_me_current 1489
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 281742
telemt_upstream_connect_attempt_total 85902
telemt_upstream_connect_success_total 85209
telemt_upstream_connect_fail_total 568
telemt_upstream_connect_attempts_per_request{bucket="1"} 85777
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 46847
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35418
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 910
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2034
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 568
telemt_me_reconnect_attempts_total 9029
telemt_me_reconnect_success_total 2091
telemt_me_reader_eof_total 1947
telemt_me_idle_close_by_peer_total 1947
telemt_me_seq_mismatch_total 75
telemt_me_route_drop_no_conn_total 5451767
telemt_me_route_drop_channel_closed_total 350
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8446105
telemt_me_endpoint_quarantine_total 1219
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 42
telemt_me_single_endpoint_outage_exit_total 42
telemt_me_single_endpoint_outage_reconnect_attempt_total 42
telemt_me_single_endpoint_outage_reconnect_success_total 40
telemt_me_single_endpoint_quarantine_bypass_total 42
telemt_me_single_endpoint_shadow_rotate_total 1197
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 51
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
telemt_desync_total 38505
telemt_desync_full_logged_total 12440
telemt_desync_suppressed_total 26065
telemt_desync_frames_bucket_total{bucket="1_2"} 9585
telemt_desync_frames_bucket_total{bucket="3_10"} 14337
telemt_desync_frames_bucket_total{bucket="gt_10"} 14583
telemt_pool_swap_total 169
telemt_pool_force_close_total 4725
telemt_pool_stale_pick_total 360
telemt_me_writer_close_signal_drop_total 610
telemt_me_draining_writers_reap_progress_total 53564
telemt_me_writer_removed_unexpected_total 1972
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5545
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 50061
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4286
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 439
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 48839
telemt_me_writer_teardown_success_total{mode="normal"} 55606
telemt_me_writer_teardown_noop_total 53569
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 106644
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 108296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 108808
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 109125
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 109175
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 109175
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 109175
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 109175
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 109175
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 109175
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 109175
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 109175
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 109175
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 16.627350
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 109175
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 610
telemt_me_refill_failed_total 356
telemt_me_writer_restored_same_endpoint_total 1692
telemt_me_writer_restored_fallback_total 101
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 128
telemt_me_writer_removed_unexpected_minus_restored_total 179
telemt_user_connections_total{user="hello"} 8452033
telemt_user_connections_current{user="hello"} 1489
telemt_user_octets_from_client{user="hello"} 148665187745 (138.46 GB)
telemt_user_octets_to_client{user="hello"} 3231439189259 (2.94 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 605
telemt_user_unique_ips_recent_window{user="hello"} 214
```