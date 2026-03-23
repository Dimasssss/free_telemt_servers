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

# Server Metrics 2026-03-23 02:47:36 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 106872.6 (29h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3659758
telemt_connections_bad_total 346959
telemt_connections_current 915
telemt_connections_me_current 915
telemt_handshake_timeouts_total 116860
telemt_upstream_connect_attempt_total 39837
telemt_upstream_connect_success_total 39836
telemt_upstream_connect_attempts_per_request{bucket="1"} 39836
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13889
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25812
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 92
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 451
telemt_me_reconnect_attempts_total 1420
telemt_me_reconnect_success_total 622
telemt_me_reader_eof_total 639
telemt_me_idle_close_by_peer_total 639
telemt_me_route_drop_no_conn_total 3003448
telemt_me_route_drop_channel_closed_total 1234
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2996405
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_endpoint_quarantine_total 756
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 834
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 28
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
telemt_desync_total 12909
telemt_desync_full_logged_total 4089
telemt_desync_suppressed_total 8820
telemt_desync_frames_bucket_total{bucket="1_2"} 3430
telemt_desync_frames_bucket_total{bucket="3_10"} 4713
telemt_desync_frames_bucket_total{bucket="gt_10"} 4766
telemt_pool_swap_total 118
telemt_pool_force_close_total 3609
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 670
telemt_me_draining_writers_reap_progress_total 36482
telemt_me_writer_removed_unexpected_total 616
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2600
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 34147
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3553
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 56
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 32873
telemt_me_writer_teardown_success_total{mode="normal"} 36747
telemt_me_writer_teardown_noop_total 36493
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 59552
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 61931
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 64098
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 68090
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 71051
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 72736
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 73235
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 73240
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 73240
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 73240
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 73240
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 73240
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 73240
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 379.457449
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 73240
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 670
telemt_me_refill_failed_total 42
telemt_me_writer_restored_same_endpoint_total 557
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 58
telemt_user_connections_total{user="hello"} 2985329
telemt_user_connections_current{user="hello"} 915
telemt_user_octets_from_client{user="hello"} 42582389052 (39.66 GB)
telemt_user_octets_to_client{user="hello"} 815634777568 (759.62 GB)
telemt_user_unique_ips_current{user="hello"} 439
telemt_user_unique_ips_recent_window{user="hello"} 154
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 120239.1 (33h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4031771
telemt_connections_bad_total 372357
telemt_connections_current 282
telemt_connections_me_current 282
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 101367
telemt_upstream_connect_attempt_total 74753
telemt_upstream_connect_success_total 73841
telemt_upstream_connect_fail_total 805
telemt_upstream_connect_attempts_per_request{bucket="1"} 74646
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40915
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32709
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 217
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 805
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 10410
telemt_me_reconnect_success_total 3716
telemt_me_reader_eof_total 3700
telemt_me_idle_close_by_peer_total 3700
telemt_me_route_drop_no_conn_total 3645164
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3202593
telemt_me_endpoint_quarantine_total 969
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_outage_enter_total 48
telemt_me_single_endpoint_outage_exit_total 48
telemt_me_single_endpoint_outage_reconnect_attempt_total 49
telemt_me_single_endpoint_outage_reconnect_success_total 47
telemt_me_single_endpoint_quarantine_bypass_total 49
telemt_me_single_endpoint_shadow_rotate_total 945
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 43
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
telemt_desync_total 13059
telemt_desync_full_logged_total 7337
telemt_desync_suppressed_total 5722
telemt_desync_frames_bucket_total{bucket="1_2"} 2965
telemt_desync_frames_bucket_total{bucket="3_10"} 5127
telemt_desync_frames_bucket_total{bucket="gt_10"} 4967
telemt_pool_swap_total 113
telemt_pool_force_close_total 3180
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 255
telemt_me_draining_writers_reap_progress_total 49905
telemt_me_writer_removed_unexpected_total 3627
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6452
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 47116
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2722
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 458
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 46725
telemt_me_writer_teardown_success_total{mode="normal"} 53568
telemt_me_writer_teardown_noop_total 49906
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 101512
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 102754
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 103088
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 103396
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 103459
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 103472
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 103474
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 103474
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 103474
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 103474
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 103474
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 103474
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 103474
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.665707
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 103474
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 255
telemt_me_refill_failed_total 262
telemt_me_writer_restored_same_endpoint_total 3297
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 299
telemt_user_connections_total{user="hello"} 3215951
telemt_user_connections_current{user="hello"} 282
telemt_user_octets_from_client{user="hello"} 43311998610 (40.34 GB)
telemt_user_octets_to_client{user="hello"} 798252077366 (743.43 GB)
telemt_user_msgs_from_client{user="hello"} 49767
telemt_user_msgs_to_client{user="hello"} 185105
telemt_user_unique_ips_current{user="hello"} 200
telemt_user_unique_ips_recent_window{user="hello"} 70
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 195099.2 (54h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16419444
telemt_connections_bad_total 1666235
telemt_connections_current 991
telemt_connections_me_current 991
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 399129
telemt_upstream_connect_attempt_total 87822
telemt_upstream_connect_success_total 87715
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 87732
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 42866
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 43118
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1724
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 3048
telemt_me_reconnect_success_total 1623
telemt_me_reader_eof_total 1571
telemt_me_idle_close_by_peer_total 1569
telemt_me_route_drop_no_conn_total 14057351
telemt_me_route_drop_channel_closed_total 145
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 13034083
telemt_me_endpoint_quarantine_total 1307
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1471
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 46
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
telemt_desync_total 54100
telemt_desync_full_logged_total 17229
telemt_desync_suppressed_total 36871
telemt_desync_frames_bucket_total{bucket="1_2"} 12066
telemt_desync_frames_bucket_total{bucket="3_10"} 21131
telemt_desync_frames_bucket_total{bucket="gt_10"} 20903
telemt_pool_swap_total 211
telemt_pool_force_close_total 6855
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 1069
telemt_me_draining_writers_reap_progress_total 66995
telemt_me_writer_removed_unexpected_total 1510
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5658
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 62127
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 45
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 6385
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 60140
telemt_me_writer_teardown_success_total{mode="normal"} 67785
telemt_me_writer_teardown_noop_total 67048
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 123645
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 127335
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 129112
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 131505
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 133172
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 134223
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 134794
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 134824
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 134825
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 134829
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 134831
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 134833
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 134833
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 317.934974
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 134833
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1069
telemt_me_refill_failed_total 78
telemt_me_writer_restored_same_endpoint_total 1405
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 97
telemt_user_connections_total{user="hello"} 13034068
telemt_user_connections_current{user="hello"} 991
telemt_user_octets_from_client{user="hello"} 197705596689 (184.13 GB)
telemt_user_octets_to_client{user="hello"} 3513499528055 (3.20 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 476
telemt_user_unique_ips_recent_window{user="hello"} 109
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 195100.4 (54h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11962040
telemt_connections_bad_total 1253153
telemt_connections_current 701
telemt_connections_me_current 701
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 345333
telemt_upstream_connect_attempt_total 102104
telemt_upstream_connect_success_total 100769
telemt_upstream_connect_fail_total 882
telemt_upstream_connect_attempts_per_request{bucket="1"} 101651
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 53813
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 42965
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 188
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3803
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 882
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 225
telemt_me_reconnect_attempts_total 4480
telemt_me_reconnect_success_total 1930
telemt_me_reader_eof_total 1796
telemt_me_idle_close_by_peer_total 1796
telemt_me_route_drop_no_conn_total 4565063
telemt_me_route_drop_channel_closed_total 498
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8865447
telemt_me_endpoint_quarantine_total 1324
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1492
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 54
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
telemt_desync_total 39056
telemt_desync_full_logged_total 13155
telemt_desync_suppressed_total 25901
telemt_desync_frames_bucket_total{bucket="1_2"} 9674
telemt_desync_frames_bucket_total{bucket="3_10"} 15000
telemt_desync_frames_bucket_total{bucket="gt_10"} 14382
telemt_pool_swap_total 208
telemt_pool_force_close_total 6205
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 714
telemt_me_draining_writers_reap_progress_total 65117
telemt_me_writer_removed_unexpected_total 1823
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5744
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 61055
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5693
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 512
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 58912
telemt_me_writer_teardown_success_total{mode="normal"} 66799
telemt_me_writer_teardown_noop_total 65142
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 125175
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 128417
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 129566
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 130757
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 131516
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 131856
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 131931
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 131933
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 131939
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 131941
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 131941
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 131941
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 131941
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 104.536457
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 131941
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 714
telemt_me_refill_failed_total 137
telemt_me_writer_restored_same_endpoint_total 1653
telemt_me_writer_restored_fallback_total 20
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 150
telemt_user_connections_total{user="hello"} 8803162
telemt_user_connections_current{user="hello"} 701
telemt_user_octets_from_client{user="hello"} 218196039868 (203.21 GB)
telemt_user_octets_to_client{user="hello"} 3978310221259 (3.62 TB)
telemt_user_msgs_from_client{user="hello"} 124042
telemt_user_msgs_to_client{user="hello"} 140191
telemt_user_unique_ips_current{user="hello"} 321
telemt_user_unique_ips_recent_window{user="hello"} 78
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 195064.3 (54h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11116116
telemt_connections_bad_total 989998
telemt_connections_current 511
telemt_connections_me_current 511
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 346115
telemt_upstream_connect_attempt_total 86536
telemt_upstream_connect_success_total 84972
telemt_upstream_connect_fail_total 205
telemt_upstream_connect_attempts_per_request{bucket="1"} 85177
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39072
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 41499
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2037
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2364
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 205
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 1420
telemt_me_reconnect_attempts_total 5796
telemt_me_reconnect_success_total 2417
telemt_me_reader_eof_total 2162
telemt_me_idle_close_by_peer_total 2161
telemt_me_route_drop_no_conn_total 5344789
telemt_me_route_drop_channel_closed_total 383
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8393876
telemt_me_endpoint_quarantine_total 1372
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 38
telemt_me_single_endpoint_outage_reconnect_success_total 32
telemt_me_single_endpoint_quarantine_bypass_total 38
telemt_me_single_endpoint_shadow_rotate_total 1452
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 69
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
telemt_desync_total 38284
telemt_desync_full_logged_total 12689
telemt_desync_suppressed_total 25595
telemt_desync_frames_bucket_total{bucket="1_2"} 9675
telemt_desync_frames_bucket_total{bucket="3_10"} 14656
telemt_desync_frames_bucket_total{bucket="gt_10"} 13953
telemt_pool_swap_total 204
telemt_pool_force_close_total 6100
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 746
telemt_me_draining_writers_reap_progress_total 65637
telemt_me_writer_removed_unexpected_total 2310
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6496
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 61385
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5529
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 571
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 59537
telemt_me_writer_teardown_success_total{mode="normal"} 67881
telemt_me_writer_teardown_noop_total 65708
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 127748
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 130471
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 131434
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 132507
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 133108
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 133322
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 133450
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 133481
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 133489
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 133502
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 133535
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 133538
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 133589
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3174.857655
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 133589
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 746
telemt_me_refill_failed_total 179
telemt_me_writer_restored_same_endpoint_total 2104
telemt_me_writer_restored_fallback_total 17
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 189
telemt_user_connections_total{user="hello"} 8385797
telemt_user_connections_current{user="hello"} 511
telemt_user_octets_from_client{user="hello"} 193051631419 (179.79 GB)
telemt_user_octets_to_client{user="hello"} 3482617358517 (3.17 TB)
telemt_user_msgs_from_client{user="hello"} 46587
telemt_user_msgs_to_client{user="hello"} 113900
telemt_user_unique_ips_current{user="hello"} 259
telemt_user_unique_ips_recent_window{user="hello"} 87
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 65344.7 (18h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11342399
telemt_connections_bad_total 670284
telemt_connections_current 1068
telemt_connections_me_current 1068
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 285825
telemt_upstream_connect_attempt_total 61055
telemt_upstream_connect_success_total 57888
telemt_upstream_connect_fail_total 2055
telemt_upstream_connect_attempts_per_request{bucket="1"} 59943
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29691
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20661
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6019
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2055
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 7886
telemt_me_reconnect_success_total 1334
telemt_me_reader_eof_total 869
telemt_me_idle_close_by_peer_total 868
telemt_me_route_drop_no_conn_total 25305000
telemt_me_route_drop_channel_closed_total 59
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9405509
telemt_me_endpoint_quarantine_total 489
telemt_me_single_endpoint_outage_enter_total 94
telemt_me_single_endpoint_outage_exit_total 94
telemt_me_single_endpoint_outage_reconnect_attempt_total 179
telemt_me_single_endpoint_outage_reconnect_success_total 47
telemt_me_single_endpoint_quarantine_bypass_total 179
telemt_me_single_endpoint_shadow_rotate_total 524
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 38
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
telemt_desync_total 16532
telemt_desync_full_logged_total 4539
telemt_desync_suppressed_total 11993
telemt_desync_frames_bucket_total{bucket="1_2"} 3146
telemt_desync_frames_bucket_total{bucket="3_10"} 6738
telemt_desync_frames_bucket_total{bucket="gt_10"} 6648
telemt_pool_swap_total 67
telemt_pool_force_close_total 2150
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 493
telemt_me_draining_writers_reap_progress_total 21339
telemt_me_writer_removed_unexpected_total 1223
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2776
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19732
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1829
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 321
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19189
telemt_me_writer_teardown_success_total{mode="normal"} 22508
telemt_me_writer_teardown_noop_total 21358
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 39898
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 41710
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 42442
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 43321
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 43687
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 43810
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 43866
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 43866
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 43866
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 43866
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 43866
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 43866
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 43866
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 54.007945
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 43866
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 493
telemt_me_refill_failed_total 341
telemt_me_writer_restored_same_endpoint_total 878
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3149
telemt_me_writer_removed_unexpected_minus_restored_total 332
telemt_user_connections_total{user="hello"} 9431351
telemt_user_connections_current{user="hello"} 1068
telemt_user_octets_from_client{user="hello"} 87785062338 (81.76 GB)
telemt_user_octets_to_client{user="hello"} 631426442382 (588.06 GB)
telemt_user_msgs_from_client{user="hello"} 68321
telemt_user_msgs_to_client{user="hello"} 57932
telemt_user_unique_ips_current{user="hello"} 460
telemt_user_unique_ips_recent_window{user="hello"} 136
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 195070.9 (54h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11072218
telemt_connections_bad_total 966634
telemt_connections_current 867
telemt_connections_me_current 867
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 244193
telemt_upstream_connect_attempt_total 115314
telemt_upstream_connect_success_total 114130
telemt_upstream_connect_fail_total 1009
telemt_upstream_connect_attempts_per_request{bucket="1"} 115139
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 67566
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 44960
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1366
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1009
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 73183
telemt_me_reconnect_success_total 3146
telemt_me_reader_eof_total 2843
telemt_me_idle_close_by_peer_total 2841
telemt_me_route_drop_no_conn_total 5273194
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8724397
telemt_me_endpoint_quarantine_total 1320
telemt_me_single_endpoint_outage_enter_total 44
telemt_me_single_endpoint_outage_exit_total 44
telemt_me_single_endpoint_outage_reconnect_attempt_total 46
telemt_me_single_endpoint_outage_reconnect_success_total 44
telemt_me_single_endpoint_quarantine_bypass_total 46
telemt_me_single_endpoint_shadow_rotate_total 1478
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 55
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
telemt_me_writers_active_current 46
telemt_desync_total 46486
telemt_desync_full_logged_total 15955
telemt_desync_suppressed_total 30531
telemt_desync_frames_bucket_total{bucket="1_2"} 9451
telemt_desync_frames_bucket_total{bucket="3_10"} 17792
telemt_desync_frames_bucket_total{bucket="gt_10"} 19243
telemt_pool_swap_total 200
telemt_pool_force_close_total 5814
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 671
telemt_me_draining_writers_reap_progress_total 69623
telemt_me_writer_removed_unexpected_total 2863
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 7029
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 65501
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5065
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 749
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 63809
telemt_me_writer_teardown_success_total{mode="normal"} 72530
telemt_me_writer_teardown_noop_total 69624
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 140000
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 141418
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 141837
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 142110
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 142144
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 142147
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 142147
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 142150
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 142154
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 142154
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 142154
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 142154
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 142154
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.308128
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 142154
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 671
telemt_me_refill_failed_total 4310
telemt_me_writer_restored_same_endpoint_total 2649
telemt_me_writer_restored_fallback_total 53
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7367
telemt_me_writer_removed_unexpected_minus_restored_total 161
telemt_user_connections_total{user="hello"} 8727285
telemt_user_connections_current{user="hello"} 867
telemt_user_octets_from_client{user="hello"} 196405615605 (182.92 GB)
telemt_user_octets_to_client{user="hello"} 3335321369280 (3.03 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 395
telemt_user_unique_ips_recent_window{user="hello"} 100
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 131907.2 (36h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11783474
telemt_connections_bad_total 483491
telemt_connections_current 651
telemt_connections_me_current 651
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4777550
telemt_upstream_connect_attempt_total 63979
telemt_upstream_connect_success_total 63515
telemt_upstream_connect_fail_total 452
telemt_upstream_connect_attempts_per_request{bucket="1"} 63967
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33710
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29580
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 225
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 452
telemt_me_reconnect_attempts_total 49118
telemt_me_reconnect_success_total 1884
telemt_me_reader_eof_total 1561
telemt_me_idle_close_by_peer_total 1560
telemt_me_route_drop_no_conn_total 4102123
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5662050
telemt_me_endpoint_quarantine_total 903
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 1016
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
telemt_me_writers_active_current 48
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 31847
telemt_desync_full_logged_total 10883
telemt_desync_suppressed_total 20964
telemt_desync_frames_bucket_total{bucket="1_2"} 6353
telemt_desync_frames_bucket_total{bucket="3_10"} 12569
telemt_desync_frames_bucket_total{bucket="gt_10"} 12925
telemt_pool_swap_total 140
telemt_pool_force_close_total 4020
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 381
telemt_me_draining_writers_reap_progress_total 49231
telemt_me_writer_removed_unexpected_total 1606
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3965
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 46921
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3579
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 441
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 45211
telemt_me_writer_teardown_success_total{mode="normal"} 50886
telemt_me_writer_teardown_noop_total 49238
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 98828
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 99587
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 99897
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 100124
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 100124
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 100124
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 100124
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 100124
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 100124
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 100124
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 100124
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 100124
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 100124
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.728877
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 100124
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 381
telemt_me_refill_failed_total 2744
telemt_me_writer_restored_same_endpoint_total 1666
telemt_me_writer_restored_fallback_total 30
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5654152
telemt_user_connections_current{user="hello"} 651
telemt_user_octets_from_client{user="hello"} 120280315688 (112.02 GB)
telemt_user_octets_to_client{user="hello"} 2195927236922 (2.00 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 308
telemt_user_unique_ips_recent_window{user="hello"} 92
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 112878.1 (31h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1563833
telemt_connections_bad_total 36941
telemt_connections_current 511
telemt_connections_me_current 511
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 32179
telemt_upstream_connect_attempt_total 53491
telemt_upstream_connect_success_total 53324
telemt_upstream_connect_fail_total 139
telemt_upstream_connect_attempts_per_request{bucket="1"} 53463
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24938
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27585
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 801
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 139
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2322
telemt_me_reconnect_success_total 952
telemt_me_reader_eof_total 942
telemt_me_idle_close_by_peer_total 942
telemt_me_route_drop_no_conn_total 526653
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1390337
telemt_me_endpoint_quarantine_total 955
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 937
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 16
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
telemt_desync_total 9664
telemt_desync_full_logged_total 2750
telemt_desync_suppressed_total 6914
telemt_desync_frames_bucket_total{bucket="1_2"} 2943
telemt_desync_frames_bucket_total{bucket="3_10"} 3657
telemt_desync_frames_bucket_total{bucket="gt_10"} 3064
telemt_pool_swap_total 122
telemt_pool_force_close_total 3079
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 173
telemt_me_draining_writers_reap_progress_total 45453
telemt_me_writer_removed_unexpected_total 907
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3448
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 42954
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2991
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 42374
telemt_me_writer_teardown_success_total{mode="normal"} 46402
telemt_me_writer_teardown_noop_total 45457
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 90869
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 91592
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 91822
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 91859
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 91859
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 91859
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 91859
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 91859
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 91859
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 91859
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 91859
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 91859
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 91859
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.425482
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 91859
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 173
telemt_me_refill_failed_total 76
telemt_me_writer_restored_same_endpoint_total 812
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 74
telemt_user_connections_total{user="hello"} 1386092
telemt_user_connections_current{user="hello"} 511
telemt_user_octets_from_client{user="hello"} 26379669989 (24.57 GB)
telemt_user_octets_to_client{user="hello"} 586592127351 (546.31 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 210
telemt_user_unique_ips_recent_window{user="hello"} 77
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 195075.6 (54h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13396114
telemt_connections_bad_total 1622272
telemt_connections_current 709
telemt_connections_me_current 709
telemt_handshake_timeouts_total 391284
telemt_upstream_connect_attempt_total 77853
telemt_upstream_connect_success_total 77499
telemt_upstream_connect_fail_total 218
telemt_upstream_connect_attempts_per_request{bucket="1"} 77717
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38261
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39134
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 100
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 218
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 3068
telemt_me_reconnect_success_total 1545
telemt_me_reader_eof_total 1530
telemt_me_idle_close_by_peer_total 1530
telemt_me_route_drop_no_conn_total 4490320
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 42
telemt_me_route_drop_queue_full_profile_total{profile="high"} 42
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10088189
telemt_me_endpoint_quarantine_total 1421
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1478
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
telemt_me_writers_active_current 46
telemt_desync_total 42303
telemt_desync_full_logged_total 13814
telemt_desync_suppressed_total 28489
telemt_desync_frames_bucket_total{bucket="1_2"} 10285
telemt_desync_frames_bucket_total{bucket="3_10"} 15538
telemt_desync_frames_bucket_total{bucket="gt_10"} 16480
telemt_pool_swap_total 216
telemt_pool_force_close_total 5694
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 684
telemt_me_draining_writers_reap_progress_total 70424
telemt_me_writer_removed_unexpected_total 1465
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5483
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 66461
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5520
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 64730
telemt_me_writer_teardown_success_total{mode="normal"} 71944
telemt_me_writer_teardown_noop_total 70426
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 139751
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 141478
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 141861
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 142237
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 142357
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 142370
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 142370
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 142370
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 142370
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 142370
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 142370
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 142370
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 142370
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.833147
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 142370
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 684
telemt_me_refill_failed_total 82
telemt_me_writer_restored_same_endpoint_total 1358
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 91
telemt_user_connections_total{user="hello"} 10054841
telemt_user_connections_current{user="hello"} 709
telemt_user_octets_from_client{user="hello"} 195092798888 (181.69 GB)
telemt_user_octets_to_client{user="hello"} 4471815168328 (4.07 TB)
telemt_user_unique_ips_current{user="hello"} 330
telemt_user_unique_ips_recent_window{user="hello"} 92
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 195072.1 (54h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11701760
telemt_connections_bad_total 1367574
telemt_connections_current 744
telemt_connections_me_current 744
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 313050
telemt_upstream_connect_attempt_total 105484
telemt_upstream_connect_success_total 104578
telemt_upstream_connect_fail_total 698
telemt_upstream_connect_attempts_per_request{bucket="1"} 105276
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 56876
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 44721
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2068
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 698
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 10681
telemt_me_reconnect_success_total 2644
telemt_me_reader_eof_total 2454
telemt_me_idle_close_by_peer_total 2453
telemt_me_seq_mismatch_total 102
telemt_me_route_drop_no_conn_total 5657837
telemt_me_route_drop_channel_closed_total 354
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9003706
telemt_me_endpoint_quarantine_total 1594
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 53
telemt_me_single_endpoint_outage_exit_total 53
telemt_me_single_endpoint_outage_reconnect_attempt_total 53
telemt_me_single_endpoint_outage_reconnect_success_total 51
telemt_me_single_endpoint_quarantine_bypass_total 53
telemt_me_single_endpoint_shadow_rotate_total 1483
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 57
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
telemt_me_writers_active_current 46
telemt_desync_total 42024
telemt_desync_full_logged_total 13532
telemt_desync_suppressed_total 28492
telemt_desync_frames_bucket_total{bucket="1_2"} 10878
telemt_desync_frames_bucket_total{bucket="3_10"} 15459
telemt_desync_frames_bucket_total{bucket="gt_10"} 15687
telemt_pool_swap_total 206
telemt_pool_force_close_total 5459
telemt_pool_stale_pick_total 390
telemt_me_writer_close_signal_drop_total 672
telemt_me_draining_writers_reap_progress_total 70622
telemt_me_writer_removed_unexpected_total 2494
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6853
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 66354
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4988
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 65163
telemt_me_writer_teardown_success_total{mode="normal"} 73207
telemt_me_writer_teardown_noop_total 70627
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 141143
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 142926
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 143465
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 143784
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 143834
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 143834
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 143834
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 143834
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 143834
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 143834
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 143834
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 143834
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 143834
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.519404
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 143834
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 672
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 2122
telemt_me_writer_restored_fallback_total 137
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 135
telemt_me_writer_removed_unexpected_minus_restored_total 235
telemt_user_connections_total{user="hello"} 9008256
telemt_user_connections_current{user="hello"} 744
telemt_user_octets_from_client{user="hello"} 157683131216 (146.85 GB)
telemt_user_octets_to_client{user="hello"} 3512925580602 (3.19 TB)
telemt_user_msgs_from_client{user="hello"} 103592
telemt_user_msgs_to_client{user="hello"} 254638
telemt_user_unique_ips_current{user="hello"} 291
telemt_user_unique_ips_recent_window{user="hello"} 81
```